pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello'
        tool 'ant'
        sh '${tool \'ant\'}/bin/ant all'
      }
    }
  }
}