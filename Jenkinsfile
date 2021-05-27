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

        stage('Mess') {
          steps {
            echo 'Hello 🏴‍☠️'
          }
        }

      }
    }

  }
}
