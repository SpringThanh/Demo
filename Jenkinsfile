pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/SpringThanh/Demo'
            }
        }
        stage('Build Project') {
            steps {
                script {
                    bat 'mvn clean install'
                }
            }
        }
    }
}
