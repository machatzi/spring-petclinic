pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo '"Test"'
        bat 'C:\\apache-maven-3.3.9\\bin\\mvn install'
      }
    }
  }
}