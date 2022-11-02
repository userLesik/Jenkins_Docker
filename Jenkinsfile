pipeline {
     agent any
    stages {
        stage('build and push') {
            when {
                branch 'master'
            }
            sh "docker-compose up -d docker/getting-started ."

            steps {
                 {
                    sh("docker push docker/getting-started")
                }
            }
        }
    }
}
