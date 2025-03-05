pipeline {
    agent any

    stages {
        stage('Récupération du code') {
            steps {
                checkout scm
            }
        } // Closing brace for the 'Récupération du code' stage

        stage('Build') {
            steps {
                bat 'mvn test'
            }
        } 
    } 
} 
