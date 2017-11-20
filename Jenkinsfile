pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        timestamps()
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