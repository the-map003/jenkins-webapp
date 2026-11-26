pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo "Source code checked out from Git."
            }
        }
        stage('Install') {
            steps {
                echo "Installing dependencies..."
                // Use 'bat' on Windows or 'sh' on Linux/macOS
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo "Running automated tests..."
                sh 'npm test'
            }
        }
        stage('Build') {
            steps {
                echo "Building the web application..."
                sh 'ls -la'
            }
        }
    }
}