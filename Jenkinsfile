pipeline {

    agent any

    stages {

        stage ("build/compile"){
            steps {
                echo 'Compiling teh Java source code'
                sh 'javac Hello.java'
            }
        }

        stage ('run'){
            steps {
                echo 'Running teh compiled Java code...'
                sh 'java Hello'
            }
        }
    }
}