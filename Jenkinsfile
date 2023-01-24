pipeline {
    agent {
        any 
    }
    stages {      
        stage('run') {
            steps {
                ws("/var/jenkins_workspace")
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python --version'
                sh 'python pipeline.py'
                echo 'finnesh'
            }
        }
    }
}
