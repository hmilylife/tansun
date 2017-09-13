pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://code.aliyun.com/tansun/itom-fe.git', branch: 'dev', changelog: true, poll: true)
      }
    }
  }
}