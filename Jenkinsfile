pipeline {
  agent any
  stages {
    stage('Run cmake') {
      steps {
        sh '''cd module-naam
cmake .'''
      }
    }
    stage('Build') {
      steps {
        sh 'make'
      }
    }
  }
}