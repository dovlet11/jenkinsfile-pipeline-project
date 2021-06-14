pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac demo.java'
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