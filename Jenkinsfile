pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Ameyameshram16/Jenkinss_demo.git'
            }
        }

        stage('Build') {
            steps {
                sh 'ls -l'
                sh 'cat index.html'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Checking if index.html exists"'
                sh 'test -f index.html'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploy step will come next"'
            }
        }
    }
}
