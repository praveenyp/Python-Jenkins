pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                checkout scm
            }
        }

        stage('Check Python Version') {
            steps {
                bat 'python --version'
            }
        }

        stage('Run Python Script') {
            steps {
                bat 'python app.py'
            }
        }
    }
}
