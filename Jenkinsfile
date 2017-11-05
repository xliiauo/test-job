pipeline {
  options { buildDiscarder(logRotator(numToKeepStr: '10')) }
  agent { docker { image 'node:7-alpine' } }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}
