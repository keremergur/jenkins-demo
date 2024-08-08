pipeline {
    agent {
        docker { image 'python:3.10-alpine' }
    }
    stages {
        stage('Run Script') {
            steps {
                sh 'python3 --version'
            }
        }
    }
}