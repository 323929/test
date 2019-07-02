pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'test'
          }
        }
        stage('bulid') {
          steps {
            echo 'buliding'
          }
        }
      }
    }
    stage('check') {
      steps {
        echo 'checking'
      }
    }
    stage('deploy') {
      steps {
        echo 'deploying'
      }
    }
  }
}