pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Downloading code from GitHub'
            }
        }

        stage('Build') {
            steps {
                sh 'ls -la'
            }
        }

        stage('Success') {
            steps {
                echo 'Webhook Trigger Successful'
            }
        }
    }
}
