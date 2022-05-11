pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/mvieira4/jenkins-test.git', branch: 'main')
        sh 'python test.py'
      }
    }

  }
}