pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        withMaven(jdk: 'jdk11', maven: 'maven installer') {
          sh 'mvn compile'
        }

      }
    }

  }
  environment {
    Author = 'Gurpreet'
  }
}