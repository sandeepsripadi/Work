pipeline {
    agent {
        agent { docker { image 'python:3.5.1' } }
    }
    stages {
        
          stage('Py Build') {
            steps {
                sh 'python new.py'
           
        }
    }   
    }
}
