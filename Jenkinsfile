pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh '''label node1

echo \'hello syed\''''
          }
        }

        stage('stage2') {
          steps {
            sh '''label node1
echo \'hello mahesh\'
'''
          }
        }

      }
    }

    stage('stage3') {
      steps {
        sh '''label node1

echo \'hello hussain\''''
      }
    }

  }
}