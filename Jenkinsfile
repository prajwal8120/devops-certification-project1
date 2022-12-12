pipeline {
    agent any 
    stages{
    stage('checkout the project') {
      steps {
        git 'https://github.com/prajwal8120/devops-certification-project1.git'
      }
    }
  }
    stage('Build Package') {
      steps {
        sh 'mvn clean package'
      }
    }
} 
