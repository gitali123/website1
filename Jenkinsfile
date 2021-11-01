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
}
}

