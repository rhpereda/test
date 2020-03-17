pipeline {
    agent {
        label "docker"
    }
    stages {
        stage('run docker') {
            steps {
                sh 'docker run hello-world'
            }
        }
    }
}