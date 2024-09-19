pipeline {
  agent any 
stages {
  stage("Back end")
    agent {
      docker {image "maven:latest"}
        steps {
          sh 'mvn -version'
              }
            }
        }
}
      
