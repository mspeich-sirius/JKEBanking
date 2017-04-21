pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello'
        tool 'ant'
        sh '$ant all'
      }
    }
  }
}