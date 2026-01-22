pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo 'Cloning source code from GitHub'
                checkout scm
            }
        }

        stage('Verify Files') {
            steps {
                echo 'Listing files'
                sh 'ls -l'
                sh 'cat README.md'
            }
        }

        stage('Build Complete') {
            steps {
                echo 'Pipeline executed successfully'
            }
        }
    }
}
