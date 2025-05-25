pipeline{
  agent any
  stages{
    stage('Checkout code'){
      steps{
        git 'https://github.com/Sanjeev9620/Git-Practices'
      }  
    }
    stage('Build'){
      steps{
        sh 'echo "Building the code"'
      } 
    }
      stage('Test'){
      steps{
        sh 'echo "Testing the code"'
      } 
    }
       stage('Deploy'){
      steps{
        sh 'echo "Deploying the code"'
      } 
    }
  }
}
