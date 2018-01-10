pipeline {
  agent {
    docker {
      image 'daocloud.io/library/node'
      args '-p 3000:3000'
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
