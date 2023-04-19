pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build app'
            }
        }
      stage('test'){
        steps {
          echo 'test app'
        }
      }
      stage('build'){
        steps{
          echo 'deploy app'
        }
      }
    }
}
