pipeline {
  agent {
    node {
      label 'Build'
    }

  }
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/mvieira4/jenkins-test.git', branch: 'main')
      }
    }

  }
}