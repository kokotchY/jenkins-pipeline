pipeline {
  agent {
    docker {
      image 'python:3.5.1'
    }
    
  }
  stages {
    stage('Init') {
      steps {
        echo 'Hello world'
        sh 'pwd'
      }
    }
    stage('Build') {
      steps {
        echo 'Start build phase'
      }
    }
    stage('Test') {
      steps {
        echo 'Start test phase'
        sh 'python test.py'
      }
    }
  }
}