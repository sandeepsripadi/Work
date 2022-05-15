pipeline {
   agent {
      docker { image 'python:3.10.1-alpine' }
   }
   stages {
       stage('Build Code') {
          
           steps {
               sh 'python --version'
               sh """
               echo "Building Artifact"
               
               """
              sh 'python new.py'
           }
       }
      stage('Deploy Code') {
          steps {
               sh """
               echo "Deploying Code"
               """
          }
      }
   }
}
