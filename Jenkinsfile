 agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Read File') {
        stage('Build') {
            steps {
                bat 'echo Reading uk.text'
                bat 'type uk.text'
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
