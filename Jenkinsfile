/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'pip install -r requirements.txt'
            }
        }

        stage('Run ETL Script') {
            steps {
                bat 'python etl_script.py'
            }
        }
    }
}