pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo 'Cloning the repository...'
                checkout scm
            }
        }

        stage('List Files') {
            steps {
                echo 'Files in the workspace:'
                sh 'ls -l'
            }
        }

        stage('Build Done') {
            steps {
                echo '✅ Build stage finished!'
            }
        }
    }
}

