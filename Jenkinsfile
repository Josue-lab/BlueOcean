pipeline {
  agent any
  stages {
    stage('Step 1') {
      steps {
        sh 'echo "Hello World"'
      }
    }

    stage('Step 2') {
      steps {
        bat 'gradle init'
      }
    }

  }
}