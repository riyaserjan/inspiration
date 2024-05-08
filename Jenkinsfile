pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/riyaserjan/inspiration.git']])
            }
        }
        stage('Build') {
            steps {
                echo "This is the Build stage in Jenkins pipeline.."
            }
        }
    }
}