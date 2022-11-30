
pipeline {
    agent any
    stages {
        stage('download') {
            steps {
                sh '''
                ls
                echo "hola Bucky"
            
                '''
            }
        }
        stage('compilar') {
            steps {
                sh '''
                pwd
                echo "hola a todos"
                '''
            }
        }
        stage('testing'){
            steps{
                sh '''
                echo "Tareas de testing"
                '''
            }
        }
    
        stage('deployar') {
            steps {
                sh '''
                echo "hola"
                '''
            }
        }
        
    }
}
