pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
              sh 'cd //var/lib/jenkins'
              sh 'docker-compose up -d'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
       
    }
}
 
