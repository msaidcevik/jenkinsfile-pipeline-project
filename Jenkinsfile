pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                dir('/var/lib/jenkins/workspace/pipeline-webhook')
                    sh 'python --version'
                    sh 'python pipeline.py'
                    echo 'finnesh'
            }
        }
       
}

