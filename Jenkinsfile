pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Hello World'
      }
    }
    stage('stuff') {
      steps {
        powershell(script: 'Get-Date', returnStdout: true)
      }
    }
  }
}