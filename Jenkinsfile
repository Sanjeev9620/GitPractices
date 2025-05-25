pipeline {
  agent any
  stages {
    stage('Checkout code') {
      steps {
        git 'https://github.com/Sanjeev9620/GitPractices'
      }  
    }
    stage('Build') {
      steps {
        bat 'echo Building the code'
      } 
    }
    stage('Test') {
      steps {
        bat 'echo Testing the code'
      } 
    }
    stage('Deploy') {
      steps {
        bat 'echo Deploying the code'
      } 
    }
  }
}
