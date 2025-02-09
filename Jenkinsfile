pipeline {
    agent any

    environment {
        AWS_REGION = 'us-east-1'  // Set your AWS region
        ECR_REPOSITORY = '654654448814.dkr.ecr.us-east-1.amazonaws.com/matan'  // Set your ECR repository name
        IMAGE_TAG = 'latest'
    }

    stages {
        stage('build') {
            steps {
                sh 'sudo docker build -t FlaskImageApp:latest .'
            }
         stage('Hello') {
            steps {
                echo 'Hello World'
            }
         stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
