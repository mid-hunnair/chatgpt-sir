pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'gradlew build'
            }
        }
        stage('Test') {
            steps {
                bat 'gradlew test'
            }
        }
        stage('Run') {
            steps {
                bat 'java -jar build/libs/your-app-name.jar'
            }
        }
    }
}


