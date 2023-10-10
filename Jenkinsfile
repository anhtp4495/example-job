pipeline {
  agent any
  stages {
    stage('Init') {
      parallel {
        stage('Init') {
          steps {
            echo 'Hello World'
            dir(path: 'DE/aa') {
              lock(resource: 'a') {
                echo 'Lock'
              }

            }

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
  environment {
    a = 'a1'
  }
}