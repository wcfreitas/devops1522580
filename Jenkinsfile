pipeline{
    agent any
    stages{
        stage('NPM Install'){
            steps{
                sh '''
                    npm install --fix-missing
                    npm test
                    docker build
                    docker compose up
                '''
            }
        }
    }
} 