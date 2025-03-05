pipeline {
    agent any
    stages {

     stage('Récupération du code') {
         steps {
             checkout scm
            }
        
        stage('Build') { 
            steps {
                sh 'mvn test'
            }
        }
    }
}
