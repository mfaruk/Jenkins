pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat 'echo buildstate'
      }
    }
    stage('deploy') {
      steps {
        bat 'echo deploystate'
      }
    }
    stage('Test') {
      steps {
        bat 'echo teststage'
      }
    }
    stage('Release') {
      steps {
        bat 'echo releasestage'
      }
    }
  }
}