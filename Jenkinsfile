pipeline {
  agent any
  stages {
    stage('checkcode') {
      steps {
        git(url: 'https://github.com/ozgurkk/nextcloud', branch: 'main')
      }
    }

  }
}