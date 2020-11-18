pipeline {
    agent any

    stages {
        stage('submit Stack') {
            steps {
                sh "/usr/local/bin/aws cloudformation create-stack --stack-name s3bucket --template-body file://S3-Bucket-Creation.YAML --region 'us-east-1'"
            }
        }
    }
}
