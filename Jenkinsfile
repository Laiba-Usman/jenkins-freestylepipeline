pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Starting Build Stage'
                sh 'python3 f1.py'
            }
        }

        stage('Test') {
            steps {
                echo 'Starting Test Stage'
                sh 'python3 f2.py'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Starting Deploy Stage'
                echo 'Application deployed successfully!'
            }
        }
    }
}
