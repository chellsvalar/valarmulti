pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add commands for building the project (e.g., compilation, packaging)
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add commands for running tests
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add commands for deploying the application
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
            // Additional steps to be executed on success
        }
        failure {
            echo 'Pipeline failed! Check the logs for details.'
            // Additional steps to be executed on failure
        }
    }
}
