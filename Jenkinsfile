pipeline {
  agent any
  stages {
    stage('step1 ') {
      parallel {
        stage('step1 ') {
          steps {
            sh 'echo "step 1"'
          }
        }

        stage('branch1') {
          steps {
            sh 'echo "branch1"'
          }
        }

      }
    }

    stage('end') {
      steps {
        sh 'echo "it is done"'
      }
    }

  }
}