pipeline {
  agent any
  stages {
    stage('Configure') {
      steps {
        git(url: 'git@github.com:zhiyix/order.git', branch: 'master')
      }
    }

  }
  environment {
    MY_PATH = 'MY'
  }
}