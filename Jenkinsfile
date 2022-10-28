pipeline {
    agent any
    stages {
        stage('Deploy to remote') {
            steps{
                sh 'scp -r ${WORKSPACE}/* ubuntu@13.235.33.196'
            }
        }

    }
}
