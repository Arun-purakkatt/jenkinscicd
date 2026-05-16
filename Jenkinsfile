pipeline {
    agent any

    stages {

        stage('Run Python') {
            steps {
                bat 'python app.py'
            }
        }

        stage('Build Docker Image') {
            steps {
                bat 'docker build -t python-demo-app .'
            }
        }

    }
}
