/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker {
        image 'maven:3.9.8-eclipse-temurin-21-alpine'
        args "-u root"} }
    stages {
        stage('build') {
            steps {
                sh 'docker -v'
            }
        }
    }
}

