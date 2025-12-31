pipeline {
    agent any

    options {
        timestamps()
    }

    stages {
        stage('Checkout') {
            steps {
                echo "Source code checked out from GitHub"
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Build started"'
                sh 'ls -l'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests"'
                sh 'cat index.html'
            }
        }

        stage('Deploy (Dry Run)') {
            steps {
                sh 'echo "Deployment stage placeholder"'
            }
        }
    }

    post {
        success {
            echo "Pipeline completed successfully 🎉"
        }
        failure {
            echo "Pipeline failed ❌"
        }
    }
}


