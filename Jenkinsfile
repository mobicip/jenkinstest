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
        echo 'I am ${env.NAME}'
      }
    }
  }
  environment {
    NAME = 'SABARISH'
  }
}
