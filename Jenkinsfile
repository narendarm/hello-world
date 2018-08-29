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
        stage('error') {
          steps {
            sh '''echo "hello second"
'''
          }
        }
      }
    }
    stage('step2') {
      steps {
        sh '''echo "seq"
'''
      }
    }
  }
}