pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        nodejs('angular') {
          sh 'npm install'
        }

      }
    }

  }
}