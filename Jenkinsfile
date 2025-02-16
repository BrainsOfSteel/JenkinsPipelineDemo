pipeline {
    agent any 
    stages {
        stage('Checkout code') {
            steps {
                echo 'Checking out code.....'
                git branch: 'main', url: 'https://github.com/BrainsOfSteel/JenkinsPipelineDemo.git'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying..'
            }
        }
    }
}
