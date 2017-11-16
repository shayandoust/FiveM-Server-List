pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'gradle wrapper --gradle-version 4.3'
          }
        }
        stage('') {
          steps {
            sh './gradlew assemble'
          }
        }
      }
    }
    stage('COMPLETE') {
      steps {
        echo 'COMPLETE'
      }
    }
  }
}