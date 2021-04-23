pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo "Hello world!"'
          }
        }

        stage('test') {
          steps {
            sh 'print("Goodbye, World!")'
          }
        }

      }
    }

  }
}