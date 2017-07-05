pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        parallel(
          "Build": {
            echo 'Hello World'
            
          },
          "Stage 2": {
            echo 'hello'
            
          },
          "Stage 3": {
            echo 'no 3'
            
          }
        )
      }
    }
  }
}