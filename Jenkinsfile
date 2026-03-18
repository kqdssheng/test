pipeline {
  agent any

  stages {
    stage('Hello') {
      steps {
        echo 'Hello World'
      }
    }

    stage('Build') {
      agent {
        docker {
          image 'alpine'
        }

      }
      steps {
        sh 'echo okkk'
      }
    }

  }
}
