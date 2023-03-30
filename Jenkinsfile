pipeline {
    agent any 
    stages {
        stage('Build Docker Image') {
            steps {
                echo 'Hello worl'
                sh "docker build . -t mahesh/nginx:latest"
            }
        }
    }
}
