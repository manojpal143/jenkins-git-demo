pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo "Code checked out"
            }
        }

        stage('Build') {
            steps {
                sh 'ls -l'
            }
        }

        stage('Test') {
            steps {
                sh 'cat index.html'
            }
        }
    }
}

