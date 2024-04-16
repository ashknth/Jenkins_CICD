pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                script {
                    // Clean and install dependencies
                    sh 'npm install'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    // Run tests
                    sh 'npm test'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    // Deployment steps
                    // e.g., deploy to server
                }
            }
        }
    }
}
