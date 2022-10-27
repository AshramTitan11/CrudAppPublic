pipeline {
    agent any
    environment{
        staging_server="3.108.97.28"
    stages {
        stage('Deploy to Remote') {
            steps{
                sh 'scp ${WORKSPACE}/* ubuntu@{staging_server}:/var/www/html/'
            }
        }
    }
}
}
