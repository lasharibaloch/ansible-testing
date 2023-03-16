pipeline {
  agent {
    node {
      label 'myhost'
    }

  }
  stages {
    stage('Code Checkout ') {
      steps {
        git(url: 'https://github.com/lasharibaloch/ansible-testing.git', branch: 'main')
      }
    }

  }
}