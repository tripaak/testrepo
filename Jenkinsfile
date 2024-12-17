pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh 'csdjvsvkhfskv'
          }
        }

        stage('run performance plugin ') {
          steps {
            bzt 'locust/test.yaml'
          }
        }

      }
    }

  }
}