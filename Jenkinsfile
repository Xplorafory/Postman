pipeline {
    agent   any
        
    stages {
        stage('Postman tests') {
            steps {
                git 'https://github.com/Xplorafory/Postman.git/'
                sh 'npm install'
                sh 'npm run DemoJensen.postman_collection.json'
            }
        }
    }   
}