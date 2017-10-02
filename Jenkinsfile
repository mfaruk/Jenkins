pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat(script: 'echo build state', returnStdout: true, returnStatus: true)
      }
    }
    stage('deploy') {
      steps {
        bat(script: 'echo deploy state', returnStatus: true, returnStdout: true)
      }
    }
    stage('Test') {
      steps {
        bat(script: 'echo test stage', returnStatus: true, returnStdout: true)
      }
    }
    stage('Release') {
      steps {
        bat(script: 'echo release stage', returnStatus: true, returnStdout: true)
      }
    }
  }
}