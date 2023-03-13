pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('') {
      steps {
        sh 'sh "docker build -t mosdns:v1 ."'
      }
    }

  }
}