pipeline {
  agent {
    docker {
      image 'node:7-alpine'
      args '-p 3001:3000'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'npm install'
        echo 'hello word'
      }
    }
  }
}