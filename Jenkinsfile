pipeline {
    agent any
    tools{
        nodejs '18.9.0'
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npm run build'
                sh 'npm run start'
            }
        }
    }
}