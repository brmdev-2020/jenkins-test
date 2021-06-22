pipeline {
  agent {
    node {
      label 'jenkins-test'
    }

  }
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/brmdev-2020/jenkins-test.git', branch: 'main')
      }
    }

    stage('build') {
      steps {
        sh 'python *test.py'
      }
    }

  }
}