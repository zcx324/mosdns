pipeline {
  agent {
    node {
      label 'jenkins-node1'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'sh "docker build -t mosdns:v1 ."'
      }
    }

  }
}