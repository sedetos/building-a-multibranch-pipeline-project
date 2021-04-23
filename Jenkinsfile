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

        stage('error') {
          steps {
            dir(path: '/home/ec2-user/github/building-a-multibranch-pipeline-project')
          }
        }

      }
    }

    stage('') {
      steps {
        echo 'Step #two'
      }
    }

  }
}