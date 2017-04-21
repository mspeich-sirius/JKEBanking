pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello'
        tool 'ant'
        script {
          ${tool 'ant'} all
        }
        
      }
    }
  }
}