pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'echo Integrating Jenkins Pipeline with GitHub Webhook using Jenkinsfile'
            }
        }        
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python --version'
                sh 'python pipeline.py'
                echo 'finnesh'
            }
        }
        stage('test') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'echo Integrating Jenkins Pipeline with GitHub Webhook using Jenkinsfile'
            }
        }
    }
    post {
        always {
            cleanWs()
            dir("${env.WORKSPACE}@tmp") {
                deleteDir()
            }
        }
    }   
}

