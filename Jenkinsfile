
pipeline {
    agent any

    stages {
        stage('Checkout Confirmation') {
            steps {
                echo 'Jenkinsfile loaded from GitHub!'
            }
        }

        stage('System Check') {
            steps {
                sh 'whoami'
                sh 'date'
                sh 'free -h'
            }
        }

        stage('Finish') {
            steps {
                echo 'GitHub Pipeline practical successful!'
            }
        }
    }
}
// Testing GitHub automatic build trigger
