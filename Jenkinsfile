pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello'
        tool 'ant'
        script {
          withEnv(["PATH=${tool 'ant'}/bin"]) {
            sh "ant all"
          }
        }
        
      }
    }
  }
}