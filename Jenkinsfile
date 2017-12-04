pipeline {
    agent {
        docker {
            image 'node:6-alpine'
            args '-p 3000:3000'
        }
    }
    environment {
        CI = 'true' 
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') { 
            steps {
<<<<<<< HEAD
                sh './jenkins/scripts/test.sh' 
=======
                sh 'npm install' 
>>>>>>> f4c0b506e2bd7a969733e942c0bfa83bebfef7b4
            }
        }
    }
}