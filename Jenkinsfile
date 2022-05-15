pipeline {
   agent any
   
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
