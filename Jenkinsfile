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
                sh 'echo "sh 'cattt file_does_not_exist'..."'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }
    }
}
