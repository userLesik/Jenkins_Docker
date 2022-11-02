pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'cd //opt/nginx-ssl'
              sh 'docker-compose up -d'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
