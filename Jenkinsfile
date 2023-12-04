pipeline {
  agent any
  stages {
    stage('Build stage') {
      steps {
        build 'Build'
        echo 'Build job'
      }
    }

    stage('Test stage') {
      steps {
        echo 'Test'
      }
    }

    stage('Deploy stage') {
      steps {
        echo 'Deploy'
      }
    }

  }
}