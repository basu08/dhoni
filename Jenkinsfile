pipeline {
  agent any
  stages {
    stage('download') {
      steps {
        nodejs('angular') {
          sh 'npm install'
        }

      }
    }

  }
}