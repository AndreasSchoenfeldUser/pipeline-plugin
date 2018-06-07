pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sleep 10
        findbugs()
      }
    }
    stage('test') {
      steps {
        sleep 10
      }
    }
  }
}