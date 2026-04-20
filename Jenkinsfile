pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Cloning repository...'
                git 'https://github.com/your-username/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
                sh 'echo Build completed'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo Tests successful'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                sh 'echo Deployment done'
            }
        }
    }
}
