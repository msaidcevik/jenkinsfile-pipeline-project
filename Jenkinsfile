pipeline {
    agent {
        node {
        label 'my-label'
        customWorkspace '/my/path/to/workspace'
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
