pipeline {
    agent   any
        
    stages {
        stage('Postman tests') {
            steps {
                sh 'npm config ls'
                sh 'npm install'
                sh 'npm run api-tests-production'
            }
        }
    }   
}