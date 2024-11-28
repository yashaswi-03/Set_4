pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                script {
                    bat 'docker build -t my-nodejs-app .'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    echo 'Running tes'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    echo 'Start application'
                }
            }
        }
    }
}
