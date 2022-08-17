pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            sh 'echo "Hello Stage1"'
          }
        }

        stage('Stage1.1') {
          steps {
            sh 'echo "Hello 1.1"'
          }
        }

        stage('Stage1.2') {
          steps {
            sh 'sleep 5 && echo "1.2"'
          }
        }

      }
    }

    stage('Stage2') {
      steps {
        sh 'echo "Stage2"'
      }
    }

  }
}