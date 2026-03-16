pipeline {
    agent any

    tools {
        jdk 'jdk21'
        maven 'MAVEN'
    }

    stages {

        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }
        stage('Run Selenium Tests') {
            steps {
                bat 'mvn test'
            }
        }

    }
}