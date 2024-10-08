pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                script {
                    docker.image('maven:3.9.9-eclipse-temurin-21-alpine').inside {
                        sh 'mvn --version'
                    }
                }
            }
        }
    }
}
