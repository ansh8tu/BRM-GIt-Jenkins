pipeline {
    agent any
    stages{
        stage('Build'){
            steps{
                echo 'Building the Project'
            }
        }

        stage('Test'){
            steps{
                bat 'mvn clean'
            }
        }

        stage('Deploy'){
            steps{
                echo 'Deploying the Project'
            }
        }

        stage('Manage'){
            steps{
                echo 'Managing the Project'
            }
        }
    }
}
