pipeline {
agent any 
tools {
terraform "terraform1.0.10"
}
stages{
stage('Terraform Init') {
      steps {
        sh 'terraform --version'
      }
    }
}
}

