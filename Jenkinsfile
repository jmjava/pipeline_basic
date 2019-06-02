pipeline {
    agent { label 'java-mvn-docker' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'git status'
                sh 'sudo docker ps'
            }
        }
    }
}
