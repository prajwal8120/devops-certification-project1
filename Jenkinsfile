pipeline {
  stages {
    stage('GitHub Jenkins Ant Docker Build') {
      steps {
        git 'https://github.com/prajwal8120/devops-certification-project1.git'
        sh 'mvn clean package'
      }
    }
  }
}
