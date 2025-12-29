pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Read File') {
            steps {
                bat 'echo Reading uk.text'
                bat 'type uk.text'
            }
        }
    }
}

