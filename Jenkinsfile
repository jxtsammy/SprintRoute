pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the repository from GitHub
                git url: 'https://github.com/your-username/your-repo.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                // Replace with your build command
                sh 'make'
            }
        }
        stage('Test') {
            steps {
                // Replace with your test command
                sh 'make test'
            }
        }
    }
}
