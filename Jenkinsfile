pipeline {
    agent { docker { image 'alpine' } }
    stages {
        stage('Test Docker') {
            steps {
                sh 'echo "Hello from Docker container"'
            }
        }
    }
}
