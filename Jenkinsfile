pipeline {

  environment {
    registry = "nevincleetus/java-web-app-cicd"
    registryCredential = 'dockerhub'
    dockerImage = ''
  }

  agent any
  stages {
    stage('Cloning Git') {
      steps {
        git  'https://github.com/nevincleetus/webapp-cicd.git'
      }
    }
  } 
}
 
