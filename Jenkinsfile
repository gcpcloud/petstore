pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'hostname'
        sh 'mvn --version'  
      }
    }

  }
}
