
pipeline {
    agent any
    stages {
        
    stage('Stage 2') {
            steps {
                sh ' npm install pm2 -g ' 
            }
        }
    stage('Stage 3') {
            steps {
                sh 'npm install'
            }
        }
        
    stage('Stage 4 - Run Application') {
            steps {
                sh 'pm2 start npm --name "node-app" -- run src/index.js '
            }
        }
    }
}
