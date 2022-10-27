pipeline {
    agent { docker { image 'maven:4.0.0-openjdk-11-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
