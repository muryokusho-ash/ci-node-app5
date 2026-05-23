pipeline{
    agent any
    stages{

        stage("Install Dependencies"){
            steps{
                bat 'npm install'
            }
        }
        
        stage("Run App"){
            steps{
                bat 'node app.js'
            }
        }
        
        stage("Test App"){
            steps{
                bat 'node test.js'
            }
        }
    }
}