pipeline{
    agent any
    stages{
        stage ('Inicio'){
            step{
                bat ('echo inciando')
            }
        }
        stage ('Restore'){
            step{
                bat ('dotnet restore')
            }
        }
        stage ('buildando'){
            step{
                bat ('dotnet build')
            }
        }
    }
}