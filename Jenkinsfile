pipeline {
  agent any
  stages {
    stage('download') {
      steps {
        sh 'echo "hello"'
        nodejs 'node latest'
      }
    }

    stage('build') {
      steps {
        nodejs('latest_install') {
          sh 'ng build'
        }

      }
    }

  }
}