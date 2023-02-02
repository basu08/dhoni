pipeline {
  agent any
  stages {
    stage('download') {
      steps {
        nodejs 'angular'
        sh 'npm install'
      }
    }

    stage('build') {
      steps {
        nodejs('angular') {
          sh 'ng build'
        }

      }
    }

  }
}