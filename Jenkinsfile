pipeline {
  agent any
  stages {
    stage('Run cmake') {
      steps {
        sh '''mkdir -p build
cd build
cmake -DCMAKE_EXPORT_COMPILE_COMMANDS=yes ..'''
      }
    }
    stage('Build') {
      steps {
        sh '''cd build
make'''
      }
    }
  }
}