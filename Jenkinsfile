pipeline {
  agent any
  triggers {
    cron 'H/15 * * * *'
  }

  
  stages {
    stage('echo') {
      steps {
        echo '🏴‍ hook aye aye ☠️'
      }
    }
    stage('trigers') {
      steps {
        sh 'cat /etc/crontab'
      }
    }
  }
}
