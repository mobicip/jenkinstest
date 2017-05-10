pipeline {
  agent any
  stages {
    stage('Start') {
      steps {
        parallel(
          "para1": {
            echo 'Hello'
            
          },
          "para2": {
            echo 'World'
            
          }
        )
      }
    }
    stage('End') {
      steps {
        echo 'I am ${NAME}'
      }
    }
  }
  environment {
    NAME = 'SABARISH'
  }
}
