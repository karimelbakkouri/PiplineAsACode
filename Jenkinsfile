pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build completed'
      }
    }
    stage('test') {
      steps {
        echo 'test completed'
      }
    }
    stage('deploy') {
      steps {
        echo 'deploy completed'
        timeout(time: 5, unit: 'SECONDS') {
        sh 'sleep 10'
}
      }
    }
  }
}