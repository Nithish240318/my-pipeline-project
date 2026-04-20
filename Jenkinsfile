pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building...'
                sleep 5
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                sleep 3
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sleep 4
            }
        }

        stage('Done') {
            steps {
                echo 'Finished'
            }
        }
    }
}
