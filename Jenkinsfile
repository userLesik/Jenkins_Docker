pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
              sh 'docker run nginx'
              sh 'docker run nginx'
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
