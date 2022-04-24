pipeline {
  agent any
  stages {
    stage('Configure') {
      steps {
        git(url: 'http://192.168.1.3:3000/gitadmin/order.git', branch: 'master')
      }
    }

  }
  environment {
    MY_PATH = 'MY'
  }
}