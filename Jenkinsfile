pipeline {
     agent {
        docker { image 'node:16.13.1-alpine' }
    }
   
    stages {
         stage('Initialize'){
        def dockerHome = tool 'MyDocker'
        env.PATH = "${dockerHome}/bin:${env.PATH}"
    }
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
 }

