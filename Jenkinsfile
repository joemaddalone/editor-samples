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
            
          },
          "Stage 4": {
            echo '#4'
            
          },
          "Stage 5": {
            echo '#5'
            
          },
          "Stage 6": {
            echo '6'
            
          }
        )
      }
    }
  }
}