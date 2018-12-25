pipeline {
  agent any
  stages {
    stage('Build Beta') {
      steps {
        sh 'cd AutoDeloyApp'
        sh 'fastlane beta'
      }
    }
  }
}