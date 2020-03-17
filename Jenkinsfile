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
            sh 'mvn clean test'
       }
    }
  }
}
