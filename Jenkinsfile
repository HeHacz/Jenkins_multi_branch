  pipeline {
  agent any
  triggers {
    cron 'H/15 * * * *'
  }
  stages {
	  steps {
		echo '☠️ 🪝 🏴‍ hook aye aye ☠️'
		}
		stage('triggers') {
			steps {
				cat /etc/crontab
			}
		}

	}
}
