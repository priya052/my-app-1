pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "clean"
            }
        }
        stage('--test--') {
            steps {
                sh "test"
            }
        }
        stage('--package--') {
            steps {
                sh "package"
            }
        }
    }
}
