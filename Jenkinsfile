pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo '🔨 Đang build project...'
                sh 'javac src/HelloWorld.java'
            }
        }
        stage('Test') {
            steps {
                echo '🧪 Đang chạy test...'
                sh 'java -cp src HelloWorld'
            }
        }
        stage('Deploy') {
            steps {
                echo '🚀 Deploy thành công!'
            }
        }
    }
}
