pipeline {
  agent any
  stages {
    stage('download') {
      steps {
        nodejs 'node_latest'
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