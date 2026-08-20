pipeline {
  agent any
  stages {
    stage('Checkout code') {
      steps {
        git branch: 'main', url:'https://github.com/rochdi1/test_jenkins.git'
      }
    }
    stage('Build') {
      steps {
        echo 'Building the project...'
        echo 'Building the project2...'
      }
    }
    stage('Test') {
      steps {
        echo 'Running tests...'
        echo 'Running integration tests...'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying application...'
      }
    }
  }
}
