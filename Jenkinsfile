pipeline {
    agent { docker { image 'maven:3.8.6-openjdk-11' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
