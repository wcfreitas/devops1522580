pipeline{
    agent any
    stages{
        stage('Build TADS'){
            steps{
                sh '''
                    java --version
                    docker info
                    docker compose info
                '''
            }
        }
    }
} 