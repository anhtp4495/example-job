pipeline {
  agent any
  stages {
    stage('Init') {
      parallel {
        stage('Init') {
          steps {
            echo 'Hello World'
          }
        }

        stage('What') {
          steps {
            echo 'Do something'
          }
        }

      }
    }

  }
}