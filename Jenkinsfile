pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'git@github.com:ericsgarcia/jenkinstest.git', branch: 'master', credentialsId: 'ericsgarcia', poll: true)
      }
    }
  }
  environment {
    SW1HOME = '/mapr/houmapr/sw1'
  }
}