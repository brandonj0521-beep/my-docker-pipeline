pipeline {
  agent any

  stages {
    stage('Checkout SCM') {
      steps {
        checkout scm
      }
    }

    stage('Build Docker Image') {
      steps {
        sh 'docker build -t my-app:latest .'
      }
    }
  }
}
