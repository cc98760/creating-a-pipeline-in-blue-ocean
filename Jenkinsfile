pipeline {
  agent {
    docker {
      image 'node:7-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('') {
      steps {
        sh 'npm install'
        echo 'hello word'
      }
    }
  }
}