pipeline {
    agent {
        docker {
            image 'gradle:jdk11-slim'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh './gradlew clean build'
            }
        }
    }
}