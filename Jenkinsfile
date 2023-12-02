pipeline{
    agent any
    tools {nodejs "NodeJs"}
    stages{
        stage('NPM Install'){
            steps{
                sh '''
                
                    docker build
                    docker compose up
                '''
            }
        }
    }
} 