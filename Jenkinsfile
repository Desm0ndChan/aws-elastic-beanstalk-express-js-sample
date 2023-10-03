pipeline {
  agent {
    docker {
      image 'node:16'
    }
  }
  stages {
    stage('Build') {
      steps {
        script {
          sh 'npm install --save'
        }
      }
    }
  }
}
