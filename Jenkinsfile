pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh 'ls -l'
            }
        }

        stage('Test') {
            steps {
                sh 'test -f index.html'
            }
        }

        stage('Deploy') {
            steps {
                sh 'sudo cp index.html /usr/share/nginx/html/index.html'
            }
        }
    }
}
