pipeline {
  agent any
  stages {
    stage('Unit Test Cases') {
      parallel {
        stage('Unit Test Cases') {
          steps {
            sh 'npm test'
          }
        }

        stage('New') {
          steps {
            input 'Wait'
          }
        }

      }
    }

  }
}