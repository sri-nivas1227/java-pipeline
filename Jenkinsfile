pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'java Hello.java'
            }
        }
        stage{
            steps{
                sh 'echo "all set"'

            }
        }
    }
}