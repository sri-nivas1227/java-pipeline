pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'java Hello.java'
            }
        }
        stage('test'){
            steps{
                sh 'echo "all set"'

            }
        }
    }
}