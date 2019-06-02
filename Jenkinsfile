pipeline {
    agent { jenkins-java-maven-docker }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
