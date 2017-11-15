pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'gradle build'
      }
    }
    stage('COMPLETE') {
      steps {
        echo 'COMPLETE'
      }
    }
  }
}