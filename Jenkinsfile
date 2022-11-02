pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
              sh 'cd //opt/nginx-ssl/'
              sh 'docker compose run -e TAG=1 -d'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
       
    }
}
 
