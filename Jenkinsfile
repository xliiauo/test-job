pipeline {
  agent { node { label 'swarm-agent' } }
  stages {
    stage('Test') {
      agent {
        docker { image 'node:7-alpine' }
      }
      steps {
        sh 'node --version'
      }
    }
  }
}
