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
          stage('Py Build') {
            steps {
                sh 'python new.py'
           
        }
    }   
    }
}
