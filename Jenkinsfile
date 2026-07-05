pipeline {
    agent any

    stages {

        stage('Checkoutted') {
            steps {
                echo "cking out code..."
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building application..."'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }
    }
}
