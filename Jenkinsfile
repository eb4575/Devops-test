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
        stage('test2') {
          steps {
            echo 'test2'
          }
        }
        stage('error') {
          steps {
            sh 'date'
          }
        }
      }
    }
  }
}