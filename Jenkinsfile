pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                echo 'Running the project...'
                sh 'java HelloWorld'
            }
        }
    }
}
