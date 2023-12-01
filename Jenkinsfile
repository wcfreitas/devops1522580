pipeline{
    agent any
    stages{
        stage('NPM Install'){
            steps{
                sh '''
                    npm --version
                    node --version
                    npm install
                    npm test
                    docker build
                    docker compose up
                '''
            }
        }
    }
} 