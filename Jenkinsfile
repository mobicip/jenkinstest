pipeline {
  agent any
  stages {
    stage('Start') {
      steps {
        echo 'Start'
      }
    }
    stage('Par1') {
      steps {
        parallel(
          "Par1": {
            echo 'Hello'
            
          },
          "Par2": {
            echo 'World'
            
          }
        )
      }
    }
    stage('Fini') {
      steps {
        echo 'Bye!'
      }
    }
  }
  environment {
    NAME = 'SABARISH'
  }
}