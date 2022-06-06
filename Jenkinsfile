pipeline {
    agent any
    stages{
        stage('build') {
            steps{
                echo "First echo"
                sh 'echo second step'
                sh 'echo another step'
                sh '''
                echo 'Multiple'
                echo 'Example'
                '''
                echo 'not using shell'
            }
        }
        
    }
}
