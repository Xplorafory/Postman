pipeline {
    agent   any
        
    stages {
        stage('Postman tests') {
            steps {
                sh echo
                sh 'npm install'
                sh 'npm run api-tests-production'
            }
        }
    }   
}