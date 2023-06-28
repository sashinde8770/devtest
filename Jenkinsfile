pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh '''echo "test1"
'''
          }
        }

        stage('test') {
          steps {
            echo 'Hello world'
          }
        }

        stage('deploy') {
          steps {
            echo 'Deploy'
          }
        }

      }
    }

  }
}