pipeline {
    agent { docker { image 'node:9.11' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}