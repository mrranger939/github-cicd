pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'where python'
                bat 'where py'
                bat 'python --version'
                bat 'py --version'
            }
        }

/*         stage('Test') {
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
        } */
    }
}
