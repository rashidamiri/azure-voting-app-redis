pipeline {
    agent any

    stages {
        stage('Verify Branch'){
            steps{
                echo "$GIT_BRANCH"
            }
        }
        stage('Docker Build'){
            steps{
                sh 'whoami'
                sh(script: '/usr/local/bin/docker --version')
            }
        }
    }
}