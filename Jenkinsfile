pipeline {
    agent {
        docker { image 'node:16.13.1-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
    stages {
        stage('Py Build') {
            steps {
                sh 'new.py'
            }
        }
    }
}
