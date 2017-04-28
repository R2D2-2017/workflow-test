pipeline {
  agent any
  stages {
    stage('Hallo') {
      steps {
        echo 'Hallo'
      }
    }
    stage('') {
      steps {
        fileExists 'thisneverexists.txt'
      }
    }
  }
}