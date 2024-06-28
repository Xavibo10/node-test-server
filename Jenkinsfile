
pipeline {
    agent any
    stages {
        
    stage('Install dependencies') {
            steps {
                sh 'npm install'
            }
        }
        
    stage('Stage 4 - Run Application') {
            steps {
                sh 'sudo pm2 start npm -- start -- watch --name "my-app" '
            }
        }
    }
}
