pipeline {
  agent {
    node {
      label 'test'
    }

  }
  stages {
    stage('test') {
      steps {
        sh 'echo "test server"'
      }
    }

    stage('dev') {
      steps {
        sh 'echo "dev server"'
      }
    }

    stage('prod') {
      steps {
        sh 'echo "prod server"'
      }
    }

  }
}