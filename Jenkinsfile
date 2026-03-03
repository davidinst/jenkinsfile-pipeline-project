pipeline {

    agent any

    stages {

        stage ("build/compile"){
            steps {
                echo 'Version 2 ---- Compiling teh Java source code'
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