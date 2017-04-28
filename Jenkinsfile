pipeline {
  agent any
  stages {
    stage('Run cmake') {
      steps {
        sh '''mkdir bin
cd bin
cmake ..'''
      }
    }
    stage('Build') {
      steps {
        sh 'make'
      }
    }
  }
}