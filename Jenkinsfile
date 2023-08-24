pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // You can add more build-related steps here
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'python main.py'
            }
        }
    }
}
