pipeline {
    agent any

    triggers {
        pollSCM '* * * * *'
    } 

    stages {
        stage('Clone') {
          steps {
            echo "cloning"
            echo "repo"        
          }

        }

        stage('Build') {
          steps {
            echo "Building"
          }      
        }

        stage('Test') {
          steps {
            echo "Testing"
          }      
        }

        stage('Deploy') {
          steps {
            echo "Applying"
          }      
        }            
    } 
}