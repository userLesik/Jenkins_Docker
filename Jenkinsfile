pipeline {
     agent any
    stages {
        stage('build and push') {
            when {
                branch 'master'
            }
            sh "docker-compose up -d //opt/nginx-ssl"

            steps {
                 {
                    sh("docker push //opt/nginx-ssl")
                }
            }
        }
    }
}
