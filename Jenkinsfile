pipeline {
    agent any

    stages {
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
        stage('Deploy to remote') {
            steps {
                    sh "scp -r ${WORKSPACE}/* ubuntu@13.233.168.170"
            }
        }
    }
}
