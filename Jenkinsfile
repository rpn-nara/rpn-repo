pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
               echo "Build is successfull. Please proceed with testing" 
            }
        }
        stage('Test') {
            steps {
                echo "Test is passed and ready to deploy"
            }
        }
        stage('Deploy') {
            steps {
                echo "Code is deployed"
            }
        }
        stage('Release') {
            steps {
                echo "Finally release is successful and Site is live now"
            }
        }
    }
}
