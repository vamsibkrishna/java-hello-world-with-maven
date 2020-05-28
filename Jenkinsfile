pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'echo \'Building\''
      }
    }

    stage('Test') {
      steps {
        echo 'Echo \'Testing\';exit 1'
      }
    }

    stage('Archive') {
      steps {
        echo 'echo \'Archiving\''
      }
    }

  }
}
