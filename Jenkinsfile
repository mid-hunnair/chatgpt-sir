pipeline {
    agent any
    stages {
        stage('Install') {
            steps {
                sh 'pip install -r requirements.txt'
            }
        }
        stage('Test') {
            steps {
                sh 'pytest'
            }
        }
        stage('Run') {
            steps {
                sh 'python app.py'
            }
        }
    }
}

