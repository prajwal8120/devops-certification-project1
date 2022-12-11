pipeline {
    agent any 
    stages{
    stage('checkout the project') {
      steps {
        git 'https://github.com/prajwal8120/devops-certification-project1.git'
      }
    }
  }
    stage('build package') {
      steps {
        ssh "mvn clean package"
      }
    }
}    
