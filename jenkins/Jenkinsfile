pipeline {
    agent {
        docker {
            image 'node:6-alpine'
            args '-p 3060:3060'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
