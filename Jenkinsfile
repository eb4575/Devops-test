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
        stage('error') {
          steps {
            echo 'test2'
          }
        }
        stage('') {
          steps {
            sh 'date'
          }
        }
      }
    }
  }
}