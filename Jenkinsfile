pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Starting Application Build"
                sh 'python3 app.py'
            }
        }

        stage('Test') {
            steps {
                echo "Starting Application Testing"
                sh 'python3 test.py'
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