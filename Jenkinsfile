pipeline {
  agent any
  stages {
    stage('2') {
      parallel {
        stage('2') {
          steps {
            echo '2'
          }
        }
        stage('9') {
          steps {
            echo '9'
          }
        }
      }
    }
    stage('3') {
      steps {
        echo '3'
      }
    }
    stage('4') {
      parallel {
        stage('4') {
          steps {
            echo '4'
          }
        }
        stage('8') {
          steps {
            echo '8'
          }
        }
      }
    }
    stage('5') {
      steps {
        echo '5'
      }
    }
    stage('6') {
      steps {
        echo '6'
      }
    }
    stage('7') {
      steps {
        echo '7'
      }
    }
  }
}