pipeline {
    agent {node {label 'AGENT-1'} }
    stages {
        stage('Build') {
            steps {
                echo "Build"
            }
        }
        stage('Scan') {
            steps{
                echo "Scan Passed"
            }
        }
        stage('Test') {
            steps {
                echo "Test"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploy"
            }
        }
    }
}