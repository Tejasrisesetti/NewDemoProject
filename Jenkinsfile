pipeline {
  agent any
  
 stages {
    stage('Git Clone') {
      steps {
        git branch: 'main', url: 'https://github.com/Tejasrisesetti/NewDemoProject.git'
      }
    }
  }
 stages {
    stage('Maven Build') {
      steps {
        bat 'mvn clean package'
        bat 'mvn install'
      }
    }
  }
//  stages {
//     stage('Build Docker Image') {
//       steps {
//         sh 'docker build -t test .'
//       }
//     }
//     stage('Create Docker Container') {
//       steps {
//         sh 'docker run -d -p 8899:8899 test'
//       }
//     }
//   }
  }
}
