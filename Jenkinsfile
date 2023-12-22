pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'this is a build project'
      }
    }

    stage('test') {
      steps {
        sh '''date
pwd
git clone https://github.com/ermahen07/jenkins-demo.git
mkdir cdrom
'''
      }
    }

    stage('deploy') {
      steps {
        sh 'this is deploy project'
      }
    }

    stage('prod') {
      steps {
        echo 'this is prod project'
      }
    }

  }
  environment {
    mahender = 'kumar'
    sumit = 'saini'
  }
}