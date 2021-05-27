pipeline {
  agent any
  triggers{

      githubPush()

}
  stages {
    stage('Print') {
      parallel {
        stage('Print') {
          steps {
            sh 'echo "hook aye aye ☠️"'
          }
        }

        stage('2x🦜🦜1x🦜') {
          steps {
            echo '☠️ 🪝 🏴‍🏞️ hook aye aye🏴󠁫󠁥󠀴󠀰󠁿 ☠️'
          }
        }

      }
    }

  }
}
