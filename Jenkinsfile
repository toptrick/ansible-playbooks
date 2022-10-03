pipeline {
  agent any
  stages {
    stage('Hello') {
      parallel {
        stage('Hello') {
          agent any
          steps {
            echo 'Hello World'
            sh 'echo rahul'
          }
        }

        stage('') {
          steps {
            buildName 'Rahul Hello'
          }
        }

      }
    }

    stage('Hi') {
      parallel {
        stage('Hi') {
          steps {
            echo 'Hi'
          }
        }

        stage('') {
          steps {
            echo 'Rahul Hi'
          }
        }

      }
    }

  }
}