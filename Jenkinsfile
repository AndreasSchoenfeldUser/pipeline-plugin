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
      parallel {
        stage('test') {
          steps {
            sleep 10
          }
        }
        stage('test2') {
          steps {
            echo 'hello test 2'
          }
        }
      }
    }
  }
}