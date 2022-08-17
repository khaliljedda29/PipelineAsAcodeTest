pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build completed'
        timeout(time: 5, unit: 'SECONDS') {
    // some block
      sh'sleep 2'
        }
      }
    }
    stage('Test') {
      steps {
        echo 'Testing completed'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying completed'
      }
    }

  }
}