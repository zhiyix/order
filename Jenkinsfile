pipeline {
  agent any
  stages {
    stage('Configure') {
      steps {
        git(url: 'ssh://admin@github.com:zhiyix/order.git', branch: 'master')
      }
    }

  }
  environment {
    MY_PATH = 'MY'
  }
}