pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage ('Test') {
       steps {
            sh 'Running the testcases'
            mvn clean test -Parquillian-wildfly-managed
       }
    }
    stage('Build') {
      steps {
        sh 'hostname'
        sh 'mvn --version'
      }
    }

  }
}
