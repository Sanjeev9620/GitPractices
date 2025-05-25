pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git url: 'https://github.com/Sanjeev9620/GitPractices'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building the code"'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Testing the code"'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying the code"'
            }
        }
    }
}
