pipeline {
    agent any
    stages {
        stage('Deps') {
            steps {
	            sh 'make deps'
              }
            }
        Stage('Linter') {
             steps {
             sh 'make linter'
             }
        }
        stage('Test'){
	            steps{
               sh 'make test'
               }
              }
        	}
        }
