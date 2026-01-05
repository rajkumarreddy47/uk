pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        bat 'mvn clean compile'
      }
    }

    stage('Test') {
      steps {
        bat 'mvn test'
      }
    }
  }

  post {
    success {
      archiveArtifacts artifacts: 'target/*.jar'
    }
  }
}
