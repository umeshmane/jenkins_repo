pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        git(url: 'C:\\jenkins_repo\\hello.java', branch: 'test', credentialsId: 'test1')
      }
    }
  }
}