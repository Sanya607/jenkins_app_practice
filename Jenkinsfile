pipeline {
  agent any 
  stages {
    stage('get code'){
      steps {
        echo 'Jenkins is pulling the code from Github!'
      }
    }
    stage('Build'){
      steps {
        echo 'Building the app'
      }
    }
    stage('deploy')
    steps {
      echo 'Finally deploying!'
    }
  }
