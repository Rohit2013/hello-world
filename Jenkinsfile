pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh '''echo "This is Build Number $BUILD_NUMBER of demo $DEMO"
'''
      }
    }

  }
  environment {
    DEMO = '1'
  }
}