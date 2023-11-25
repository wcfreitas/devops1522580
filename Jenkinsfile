pipeline{
    agent any
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