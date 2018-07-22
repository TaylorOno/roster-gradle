pipeline {
  agent none
  stages {
    stage('build') {
      steps {
        git(url: 'https://github.com/TaylorOno/roster-gradle', branch: 'master', poll: true)
      }
    }
  }
}