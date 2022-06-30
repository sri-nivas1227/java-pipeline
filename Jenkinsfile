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
                retry(3){
                timeout(time:1, unit: 'MINUTES'){
                    sh 'sleep 90'
                }

            }
            }
        }
    }
}