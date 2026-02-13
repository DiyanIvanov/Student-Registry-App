pipeline {
    agent any     
    stages{
        stage("Install Dependancies"){
            steps{
                bat 'npm install'
            }
        }
        stage("Run UI tests"){
            steps{
                bat 'npm test'
            }
        }
    }
}
