pipeline {
  agent any
  stages {
    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            sh 'date'
          }
        }
        stage('') {
          steps {
            echo 'test2'
          }
        }
      }
    }
  }
}