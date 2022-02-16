pipeline {
    agent {
        docker {
            image 'maven:3-alpine'
        }
    }
    stages {
        stage('Build'){
            sh 'mvn clean package'
        }
    }
}