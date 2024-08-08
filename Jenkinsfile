pipeline {
    agent {
        docker {
            image 'python:3.11-bookworm'
        }
    }
    stages {
        stage('Run Script') {
            steps {
                sh 'python3 --version'
            }
        }
    }
}