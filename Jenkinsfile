pipeline {
  agent any
  stages {
    stage('Stage1-check time') {
      steps {
        sh '''touch job1
timedatectl'''
      }
    }

  }
  environment {
    ENV = 'DEV'
  }
}