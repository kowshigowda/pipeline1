pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh '''
                ls -lrt
                sleep 5
                '''
            }
        }
        stage('Test') { 
            steps {
               sh 'sleep 5'
            }
        }
        stage('Deploy') { 
            steps {
                sh 'sleep 5' 
            }
        }
    }
}
