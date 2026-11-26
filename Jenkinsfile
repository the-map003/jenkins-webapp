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
                bat 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo "Running automated tests..."
                bat 'npm test'
            }
        }
        stage('Build') {
            steps {
                echo "Building the web application..."
                bat 'dir'
            }
        }
    }
}