pipeline{
    agent any
    environment{
        staging_server="3.7.6.122"
    }
    stages{
        stage('Deploy to Remote'{
            steps{
                sh 'scp${WORKSOACE}/* root@${staging_server}:/var/www/html/Sahaj/'
            }
        })
    }
}