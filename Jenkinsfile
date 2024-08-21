/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'pip3 install -r requirements.txt'
            }
        }

        stage('Run ETL Script') {
            steps {
                bat 'python etl_script.py'
            }
        }
    }
}