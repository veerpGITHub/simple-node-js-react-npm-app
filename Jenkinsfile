pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
            stages {
        stage('Build') { 
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}
