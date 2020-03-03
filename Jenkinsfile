pipeline {
  agent any
  stages {
    stage('budowanie') {
      steps {
        echo 'to jest budowanie'
        git(url: 'ssh://git@bitbucket.tomtomgroup.com:7999/~maruska/api-test.git', branch: 'master', poll: true)
      }
    }

  }
}