pipeline {
agent any 
tools {
terraform "Terraform v1.0.10"
}
stages{
stage('Terraform Init') {
      steps {
        sh 'terraform --version'
      }
    }
}
}

