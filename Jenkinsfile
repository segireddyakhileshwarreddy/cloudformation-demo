pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name efsbucket --template-body file://simplests3cft.json --region 'us-east-2'"
              }
             }
            }
            }
