pipeline {
  agent any
  stages {
    stage('Checkout') {
      parallel {
        stage('Checkout') {
          steps {
            echo 'start checkout from github'
          }
        }

        stage('Build') {
          steps {
            echo 'start build'
          }
        }

        stage('Deploy') {
          steps {
            echo 'start deploy'
          }
        }

        stage('Build-Docker') {
          steps {
            echo 'start prepare docker'
          }
        }

      }
    }

  }
}