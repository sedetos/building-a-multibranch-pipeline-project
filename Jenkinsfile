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
            timestamps()
          }
        }

        stage('finalstep.') {
          steps {
            echo 'Wow, that was easy.'
          }
        }

      }
    }

  }
}