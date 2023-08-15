pipeline {
  agent any
  stages {
    stage('esso') {
      parallel {
        stage('esso') {
          steps {
            echo 'test'
          }
        }

        stage('esso4') {
          steps {
            timeout(time: 1) {
              echo 'push'
            }

          }
        }

      }
    }

    stage('esso2') {
      steps {
        echo 'build'
      }
    }

  }
}