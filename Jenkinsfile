
pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out Java source code'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Java application using Maven'
            }
        }

        stage('Test') {
            steps {
                echo 'Running unit tests'
            }
        }

        stage('Docker Build') {
            steps {
                echo 'Building Docker image'
            }
        }

        stage('Deployment') {
            steps {
                echo 'Deploying application'
            }
        }
    }
}
