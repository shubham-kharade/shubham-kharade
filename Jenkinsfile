pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'echo "Testing Code"'
      }
    }

    stage('Build') {
      steps {
        sh 'echo "Building Code"'
      }
    }

    stage('Deploy') {
      steps {
        sh 'Deploying Code'
        sleep 13
      }
    }

  }
}