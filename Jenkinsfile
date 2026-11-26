pipeline {
    agent any
    stages {
        stage('Checkout') {
           steps {
        git branch: 'master',
            credentialsId: 'github-credentials',
            url: 'https://github.com/preethii8/test.git'
           }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}