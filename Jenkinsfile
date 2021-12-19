pipeline {
    agent any

    stages {
        stage('fetch_code') {
            steps {
                git 'https://github.com/kuslapur/Maven_build.git'
            }
        }
        stage('Build') {
            steps {
               sh 'mvn clean package'    
            }
        }

      }
}
