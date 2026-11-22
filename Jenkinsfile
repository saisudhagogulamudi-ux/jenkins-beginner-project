pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout stage'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage'
                sh 'ls -l'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage'
                sh 'test -f index.html'
            }
        }

        stage('Success') {
            steps {
                echo 'Pipeline completed successfully'
            }
        }
    }
}
