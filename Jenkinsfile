pipeline {
  agent any
  stages {
    stage('Print') {
      parallel {
        stage('Print') {
          steps {
            sh 'echo "Hello World"'
          }
        }

        stage('error') {
          steps {
            echo 'Hello World'
          }
        }

      }
    }

  }
}