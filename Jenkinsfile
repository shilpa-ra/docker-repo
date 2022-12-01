pipeline {
    agent {label 'sonar'}
     stages {
        stage ('vcs') {
            steps {
                git url: "https://github.com/shilpa-ra/docker-repo.git",
                branch: "main"
              }
               }

               stage ('docker') {
                steps {
                    sh 'docker info'
                }
               }
               }
     }
