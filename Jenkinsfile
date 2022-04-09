pipeline {
  agent any
  stages {
    stage('') {
      steps {
        echo '"starting..."'
      }
    }

    stage('script') {
      steps {
        sshCommand(command: 'apt update', sudo: true)
      }
    }

  }
  environment {
    stage = 'start'
  }
}