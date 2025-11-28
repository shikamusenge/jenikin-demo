pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building the project ..."
                bat 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                bat 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying..."
                bat 'echo Deployment step running'
            }
        }
    }
}
