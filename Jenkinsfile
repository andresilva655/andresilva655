pipeline {
  agent any
  stages {
    stage('Starting') {
      steps {
        echo 'starting...'
      }
    }

    stage('Script') {
      steps {
        sh 'sh run_build_script.sh'
      }
    }

  }
  environment {
    stage = 'start'
  }
}