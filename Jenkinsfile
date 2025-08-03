pipeline {
    agent any

    stages {
        stage('Install') {
            steps {
                bat 'npm install'
            }
        }

        stage('Test') {
            steps {
                bat 'npm test || echo No tests defined'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment simulated'
            }
        }
    }
}
