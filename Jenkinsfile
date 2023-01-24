pipeline {
    agent {
        any {
            customWorkspace '/var/lib/jenkins/workspace/pipeline-webhook'
        }
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
