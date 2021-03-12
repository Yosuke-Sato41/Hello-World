pipeline {
  agent any
  stages {
    stage('First') {
      steps {
        sh 'echo "First Step"'
      }
    }

    stage('Second') {
      steps {
        sh 'echo \'Second Step\''
      }
    }

    stage('Third') {
      steps {
        sh 'echo \'Third Step\''
      }
    }

    stage('End') {
      steps {
        sh 'echo \'End Step\''
      }
    }

  }
  environment {
    chara = '1'
  }
}