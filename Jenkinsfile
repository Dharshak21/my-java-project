pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main', credentialsId: 'Git_credential', url: 'https://github.com/Dharshak21/my-java-project.git'
            }
        }

        stage('Compile') {
            steps {
                echo 'Compiling...'
                // Compile steps go here
            }
        }

        stage('Run') {
            steps {
                echo 'Running...'
                // Run steps go here
            }
        }
    }
}
