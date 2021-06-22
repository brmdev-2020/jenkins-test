pipeline {
  agent {
    node {
      label 'jenkins-test'
    }

  }
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/brmdev-2020/jenkins-test.git', branch: 'main', poll: true, changelog: true)
      }
    }

    stage('build') {
      steps {
        echo 'Building'
      }
    }

  }
}