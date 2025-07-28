pipeline {
  agent any
  stages {
    stage('step1') {
      parallel {
        stage('step1.1') {
          steps {
            echo 'step1.1'
          }
        }

        stage('step1.2') {
          steps {
            echo 'step1.2'
            sh 'step1.2.1'
            echo 'step1.2.2'
          }
        }

        stage('step1.3') {
          steps {
            echo 'step1.3'
          }
        }

      }
    }

  }
}