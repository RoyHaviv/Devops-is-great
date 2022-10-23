pipeline {
    agent { docker { image 'python:3.10.7-alpine' } }
    stages {
        stage('run') {
            steps {
                sh 'python main.py'
            }
        }
    }
}
