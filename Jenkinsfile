pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'House'
          }
        }

        stage('sub Build') {
          steps {
            echo 'sub house'
          }
        }

        stage('2apt') {
          steps {
            echo 'aight'
          }
        }

        stage('3rd apt') {
          steps {
            echo '3r'
          }
        }

        stage('4') {
          steps {
            echo 'e'
          }
        }

      }
    }

  }
}