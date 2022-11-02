pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
              sh 'cd //opt/nginx-ssl/'
              sh 'docker-compose up -d -e TAG=1'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
       
    }
}
 
