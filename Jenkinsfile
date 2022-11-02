pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
              sh 'docker.build docker/getting-started'
             
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
