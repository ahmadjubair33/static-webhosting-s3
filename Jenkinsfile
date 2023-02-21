pipeline {
    agent any
    stages {
        stage('deploy') {
            steps {
              sh "aws configure set region ap-northeast-1" 
              sh "aws configure set aws_access_key_id AKIAVESTT7FN3ACMWSKE"  
              sh "aws configure set aws_secret_access_key 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"
              sh "aws s3 cp Code/index.html s3://static-jenkins-web"
            }
        }
    }
}
