pipeline {
  agent any
  
 stages {
    stage('Git Clone') {
      steps {
        git branch: 'main', url: 'https://github.com/Tejasrisesetti/NewDemoProject.git'
      }
    }
  
    stage('Maven Build') {
      steps {
        bat 'mvn clean package'
        bat 'mvn install'
      }
    }
  }
}
