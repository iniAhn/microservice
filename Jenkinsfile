pipeline {
  agent any
  stages {
    stage('first') {
      parallel {
        stage('first') {
          steps {
            sh 'echo $JAVA_HOME'
          }
        }

        stage('first-1') {
          steps {
            echo 'hahaha'
          }
        }

      }
    }

    stage('second') {
      steps {
        sleep 5
      }
    }

  }
}