pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage ('Test') {
       steps {
            sh './mvnw test'
       }
    }
    stage ('Build') {
        steps {
            sh './mvnw package'
        }
    }
    stage {
        steps {
             sh 'java -jar target/*.jar'
        }
    }
  }
}
