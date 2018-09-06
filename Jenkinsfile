 pipeline {
agent any
 stages{
     stage("EC2_INFRA") {
            steps {
                sh "chmod 777 ec2_terraform_build.sh"
              sh "./ec2_terraform_build.sh"
            }
      }
 }
 }
