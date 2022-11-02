pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
              sh 'docker run nginx'
              sh 'docker run certbot'
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
