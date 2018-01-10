pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'daocloud.io/library/node'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }
  }
}