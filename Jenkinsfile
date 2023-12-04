pipeline {
  agent none
  stages {
    stage('Back-end') {
      agent {
        docker { image 'nginx:latest' }
      }
      steps {
        sh 'nginx --version'
      }
    }
    stage('Front-end') {
      agent {
        docker { image 'nginx:latest'  }
      }
      steps {
        sh 'nginx --version'
      }
    }
  }
}
