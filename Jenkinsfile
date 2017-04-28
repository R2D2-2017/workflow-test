pipeline {
  agent any
  stages {
    stage('Run cmake') {
      steps {
        sh 'cmake .'
      }
    }
    stage('Build') {
      steps {
        sh 'make'
      }
    }
  }
}