pipeline {
    agent any

    stages {
        stage('Check Docker Version') {
         steps {
            bat 'docker --version'
          }
         }
        stage('Verify') {
            steps {
                bat 'dir'
            }
        }
    }
}
