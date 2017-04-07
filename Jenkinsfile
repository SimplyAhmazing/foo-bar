pipeline {
  agent any
  stages {
    stage('do-it') {
      steps {
        sh 'ls -la .'
      }
    }
    stage('run-build') {
      steps {
        sh './build'
      }
    }
  }
}