pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'docker build -t mosdns:v1 .'
      }
    }

  }
}