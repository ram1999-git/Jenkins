pipeline {
    agent {
           label 'Agent-1'
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo "This is the Build stage"'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "This is the Test stage"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "This is the Deploy stage"'
            }
        }
    }
}