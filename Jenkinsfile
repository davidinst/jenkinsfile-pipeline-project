pipeline {

    agent any
    
    stages {
        stage('build') {
            steps {
                echo 'Welcome to jenkins'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}