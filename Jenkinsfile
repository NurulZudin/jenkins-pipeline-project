pipeline {
    agent { label 'linux' }
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Im Running the compiled java code.'
                sh 'java Hello'
            }
        }
    }
}





