pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               sh """
               echo "Building Artifact"
               
               """
              sh 'pyhton new.py'
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
