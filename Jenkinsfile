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