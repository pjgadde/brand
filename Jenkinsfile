pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        bat 'echo $PATH'
      }
    }
    stage('Qa') {
      steps {
        bat 'echo $USER'
      }
    }
  }
  environment {
    test = 'test'
  }
}