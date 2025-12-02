pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building application...."
                sh 'python3 app.py'
            }
        }

        stage('Test') {
            steps {
                echo "Testing application..."
                sh 'python3 test.py'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the Application"
            }
        }
    }
}