pipeline {
agent any
 stages{
     stage("EC2_INFRA") {
            steps {
            sh 'git clone https://github.com/kishanpeddaboina/Infra'
            sh '''
               cd Infra
               terraform init
               terraform apply -auto-approve -var 
               git add terraform.tfstate
        }}}
        }
            