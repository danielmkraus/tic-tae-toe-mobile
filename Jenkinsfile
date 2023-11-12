pipeline {
    agent {
        docker {
            image 'hamdifourati/cordova-android-builder:latest' 
            args '-p 3000:3000' 
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