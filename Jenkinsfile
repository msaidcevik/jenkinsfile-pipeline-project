pipeline {
    agent any
    options {
        ws("/path/to/workspace")
    }
    stages {      
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python --version'
                sh 'python pipeline.py'
                echo 'finnesh'
            }
        }
    }
}
