pipeline {
    agent any

    tools {
        jdk 'jdk21'
        maven 'MAVEN'
    }

    stages {

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

    }
}