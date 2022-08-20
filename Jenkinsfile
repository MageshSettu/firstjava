pipeline {
  agent any
  stages {
    stage('build-1') {
      parallel {
        stage('build-1') {
          steps {
            echo 'build a message in pipeline'
          }
        }

        stage('buld-2') {
          steps {
            echo 'pipeline-2nd build'
          }
        }

      }
    }

    stage('first compile') {
      steps {
        echo 'program compiled'
      }
    }

  }
}