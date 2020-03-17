pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage ('Test') {
       steps {
            #sh 'echo HI'
            #sh 'ls -l'
            sh './mvnw test'
       }
    }
  }
}
