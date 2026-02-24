pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/yourusername/yourrepo.git'
            }
        }

        stage('Run Python Script') {
            steps {
                bat 'python app.py'
                // If Linux use:
                // sh 'python3 app.py'
            }
        }
    }
}
