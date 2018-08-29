pipeline {
  agent any
  stages {
    stage('feature1') {
      parallel {
        stage('feature1') {
          steps {
            sh '''echo "hello world"
'''
          }
        }
        stage('') {
          steps {
            sh '''echo "hello second"
'''
          }
        }
      }
    }
  }
}