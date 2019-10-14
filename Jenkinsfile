pipeline {
    agent { docker { image 'node:12.3.1' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
