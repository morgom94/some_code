pipeline {
  agent any
  triggers {
   cron('H/15 * * * *')
  }
  stages {
    stage('my hook echo sample') {
      steps {
        echo 'hello from the trigger'
      }
    }

  }
}
