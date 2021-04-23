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

        stage('finalstep.') {
          steps {
            echo 'Wow, that was easy.'
          }
        }

        stage('') {
          steps {
            echo 'another one.'
          }
        }

      }
    }

    stage('error') {
      steps {
        sh '''#!/bin/sh
# This is a comment!
echo Hello World        # This is a comment, too!
'''
      }
    }

  }
}