pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Repository Loaded'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t finstream .'
            }
        }

    }
}