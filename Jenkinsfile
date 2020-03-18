pipeline {
    agent any
    stages {
        stage('run docker') {
            steps {
                sh 'docker run --rm hello-world'
            }
        }
    }
}