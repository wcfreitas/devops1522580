pipeline{
    agent any
    tools {nodejs "node"};
    stages{
        stage('NPM Install'){
            steps{
                sh '''
                    npm install
                    npm test
                    docker build
                    docker compose up
                '''
            }
        }
    }
} 