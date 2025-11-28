pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building the project ..."
                sh 'echo Build running on Linux'
                // sh 'npm install'  // if needed
            }
        }

        stage('Test') {
            steps {
                sh 'echo Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo Deploying...'
            }
        }
    }
}
