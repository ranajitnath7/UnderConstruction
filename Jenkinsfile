pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'nginx --version'
      }
    }

    stage('Done') {
      steps {
        echo 'Done MSG'
      }
    }

  }
}