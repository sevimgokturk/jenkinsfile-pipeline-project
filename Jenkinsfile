pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Integrating jenkins pipeline'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}