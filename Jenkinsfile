pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Check out your repository from GitHub
                git branch: 'main', credentialsId: 'your-github-token', url: 'https://github.com/yourusername/your-repo.git'
            }
        }
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
