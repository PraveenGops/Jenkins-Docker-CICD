pipeline {
  agent {
    docker { image "node:latest" }
  }
  stages {
    stage("Version check") {
      steps {
        sh 'node --version'
            }
        }
  }
}
