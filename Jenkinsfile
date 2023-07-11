pipeline {
  agent any

  stages {
    stage('Dotnet Restore') {
      steps {
        script {
          echo 'Hello World! 5'
        }
      }
    }

    stage('Veracode SCA Scan') {
      steps {
        echo 'Hello World! 6'
      }
    }
  }
  
  options {
    gitAuthentication('Credenciais Globais')
  }
  
  environment {
    BRANCH_NAME = 'main'
  }

  stage('Build') {
    steps {
          echo 'Hello World! 5'
    }
  }
}