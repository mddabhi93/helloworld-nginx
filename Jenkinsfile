pipeline {
    agent any 
    stages {
        stage('Build Docker Image') {
            steps {
                echo 'Hello worl'
                sh "dokcer build . -t mahesh/nginx:latest"
            }
        }
    }
}
