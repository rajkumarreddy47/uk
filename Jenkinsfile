pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                bat 'echo Build stage running'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Test stage running'
            }
        }

    }
}
