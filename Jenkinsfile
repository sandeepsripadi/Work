pipeline {
   agent any
   stages {
       stage('Build Code') {
          agent{
             docker{
                image 'python:2-alpine'
             }
          }
           steps {
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
