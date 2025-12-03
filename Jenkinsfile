pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Starting Application Build"
                bat 'py app.py'
            }
        }

        stage('Test') {
            steps {
                echo "Starting Application Testing"
                bat 'py test.py'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the Application"
                echo "Application Deployed Successfully"
            }
        }
    }
}
