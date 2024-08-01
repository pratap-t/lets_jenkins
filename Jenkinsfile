/* Requires the Docker Pipeline plugin */
pipeline {
    agent { any { image 'maven:3.9.8-eclipse-temurin-21-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version && echo hello'
            }
        }
    }
}