pipeline{
    agent any
    tools {nodejs "NodeJs"}
    stages{
        stage('NPM Install'){
            steps{
                sh '''
                    
                    npm test
                    docker build
                    docker compose up
                '''
            }
        }
    }
} 