pipeline {
    agent any

    stages {
        stage('Compile Stage') {
        steps {
                sh 'clean compile'
        }
        }
        stage('Testing Stage') {
        steps {
                sh 'test'
        }
        }
        stage('Deployment Stage') {
        steps {
                sh 'deploy'
        }
        }
    }
}