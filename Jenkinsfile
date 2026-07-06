pipeline {

    agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Display Tag') {
            steps {
                sh 'echo Building Tag: $GIT_TAG'
            }
        }

        stage('Build') {
            steps {
                sh '''
                echo "Building application..."
                '''
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                echo "Deploying version..."
                '''
            }
        }

    }

}
