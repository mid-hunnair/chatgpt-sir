pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                echo 'mvn test'
            }
        }
        stage('Run') {
            steps {
                echo 'java -jar target/your-app-name.jar'
            }
        }
    }
}



