/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:windowsservercore-ltsc2022' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}