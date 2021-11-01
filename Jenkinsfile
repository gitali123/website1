pipeline {
agent any 
tools {
terraform "terraform"
}
stages{
stage('Terraform Init') {
      steps {
        sh 'terraform --version'
      }
    }
      stage ('Terraform Plan') {
            steps {
                    sh 'terraform init'
                    sh 'terraform plan'
            }
      }
      stage ('Terraform Apply') {
            steps {
                sh 'terraform apply -auto-approve'
            }
      }
}
}

