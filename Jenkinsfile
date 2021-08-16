pipeline {
        agent {
            any
        }
        
    stages {
        stage('Postman tests') {
            steps {
                sh 'npm install'
                sh 'npm run DemoJensen.postman_collection.json'
            }
        }
    }   
}