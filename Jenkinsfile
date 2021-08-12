pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        sh 'mvn compile'
        withMaven(jdk: 'jdk11', maven: 'maven installer')
      }
    }

  }
  environment {
    Author = 'Gurpreet'
  }
}