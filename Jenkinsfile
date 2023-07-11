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
  
  tools {
    // Defina aqui as ferramentas do Jenkins que você deseja usar
    // Exemplo: dotnet 'dotnet'
  }

  // Adicione aqui as outras etapas da sua pipeline
  stage('Build') {
    steps {
      // Etapas normais da sua pipeline
    }
  }
}