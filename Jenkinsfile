pipeline {
    agent { docker { image 'python:3.7.4' } }
    stages {
        stage('build') {
            steps {
                ksh 'python3 --version'
            }
        }
    }
}
