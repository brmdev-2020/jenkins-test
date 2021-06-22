pipeline {
  agent {
    node {
      label 'jenkins-test'
    }

  }
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/brmdev-2020/jenkins-test.git', branch: 'main', credentialsId: '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')
      }
    }

    stage('build') {
      steps {
        echo 'Building'
      }
    }

  }
}