pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket_2 --template-body file://simplests3cft.json --region 'eu-central-1'"
              }
             }
            }
            }
