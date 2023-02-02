pipeline {
  agent any
  stages {
    stage('devo') {
      steps {
        nodejs 'angular'
        sh 'npm install'
      }
    }

    stage('stage') {
      steps {
        nodejs 'angular'
        sh 'ng build'
      }
    }

  }
}