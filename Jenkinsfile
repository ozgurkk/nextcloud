pipeline {
  agent any
  stages {
    stage('CheckoutCode') {
      steps {
        git(url: 'https://github.com/ozgurkk/nextcloud', branch: 'main')
      }
    }

  }
}