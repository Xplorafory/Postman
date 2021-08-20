pipeline {
    agent   any
        
    stages {
        stage('Postman tests') {
            steps {
                sh "npm install"
                sh "npm run api-tests-production"
            }
        }
    }   
}