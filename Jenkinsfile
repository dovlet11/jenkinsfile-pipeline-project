pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Demo.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Demo'
            }
        }
    }
}