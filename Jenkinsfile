pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'docker build -t mosdns:v1 .'
      }
    }

  }
}