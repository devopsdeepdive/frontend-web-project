pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/devopsdeepdive/frontend-web-project.git', branch: 'master', credentialsId: 'github-user')
      }
    }

  }
}