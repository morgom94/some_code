pipeline {
  agent any
  triggers {
   cron('H/15 * * * *')
  }
  stages {
    stage('my echo') {
      steps {
        echo 'hello from the trigger'
      }
    }

  }
}
