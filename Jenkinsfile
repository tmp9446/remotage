pipeline {
  agent any
  stages {
    stage('check-out') {
      steps {
        git(url: 'https://github.com/tmp9446/remotage.git', branch: 'python-dev')
      }
    }

    stage('Shell Script') {
      steps {
        sh 'ls -al'
      }
    }

  }
}