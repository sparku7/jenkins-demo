pipeline {

    agent any

    stages {
        stage('Make Folders and files') {
            steps {
                bat '''
                echo "Stage 1"
                '''
            }
        }
        stage('View') {
            steps {
                bat '''
                echo "Stage 2"
                '''
            }
        }
        stage('View2') {
            steps {
                bat '''
                echo "Stage 3"
                '''
            }
        }
        stage('Run') {
            steps {
                bat 'script.bat'
            }
        }
    }
}