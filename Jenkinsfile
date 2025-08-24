pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Bắt đầu Build"
                bat 'echo Building project...'
            }
        }
        stage('Test') {
            steps {
                echo "Bắt đầu Test"
                bat 'echo Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo "Bắt đầu Deploy"
                bat 'echo Deploying...'
            }
        }
    }
}
