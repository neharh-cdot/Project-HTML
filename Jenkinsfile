pipeline {
    agent any  

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from GitHub
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building the HTML page...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the HTML page...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed. Check the logs.'
        }
    }
}
