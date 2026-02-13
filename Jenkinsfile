pipeline {
    agent any     
    stages{
        stage("Install Dependancies"){
            steps{
                bat 'npm install'
            }
        }
        stage("Run security check"){
            steps{
                bat 'npm audit'
            }
        }
        stage("Run UI tests"){
            steps{
                bat 'npm test'
            }
        }
    }
}
