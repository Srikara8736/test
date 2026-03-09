pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/Srikara8736/test.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }

    }
}

