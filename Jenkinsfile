pipeline {

  environment {
    dockerimagename1 = "itzelmunguia/curso:devops"

    dockerImage1 = ""


  }

  agent any


  stages {

    stage('Checkout Source') { 
      steps {
        git credentialsId: 'githubcursodevops', url: 'https://github.com/itzelmun/ejercicio-curso-lovedevops.git', branch:'main'
      }
    }

  }}
