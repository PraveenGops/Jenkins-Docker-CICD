pipeline {
  agent none 
  stages {
    stage("Back end") {
      agent {
        docker {image "maven:latest"}
            }
          steps {
            sh 'mvn -version'
                }
              }
    stage('Front-end') {
      agent {
        docker { image 'node:16-alpine' }
      }
      steps {
        sh 'node --version'
            }
          }
} 

