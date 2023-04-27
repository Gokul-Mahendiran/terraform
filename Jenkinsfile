pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        git(url: 'https://github.com/simonqian/react-helloworld.git', branch: 'main')
      }
    }

    stage('') {
      steps {
        build 'build'
      }
    }

  }
}