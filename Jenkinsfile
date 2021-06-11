pipeline{
    agent any
    stages{
        stage ('Inicio'){
            steps{
                bat ('echo inciando')
            }
        }
        stage ('Restore'){
            steps{
                bat ('dotnet restore')
            }
        }
        stage ('buildando'){
            steps{
                bat ('dotnet build')
            }
        }
    }
}