pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        git(url: 'https://github.com/balagithub123/hello-world.git', branch: 'master', poll: true)
      }
    }

  }
}