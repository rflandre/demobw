pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''cd *.parent
mvn clean package'''
      }
    }
  }
}