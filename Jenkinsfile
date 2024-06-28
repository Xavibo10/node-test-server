
pipeline {
    agent any
    stages {
        
    stage('Satge 2') {
            steps {
                sh '''node -v
                      npm -v
              
                   ''' 
            }
        }
    stage('Stage 3') {
            steps {
                sh 'npm install'
            }
        }
        
    stage('Stage 4 - Run Application') {
            steps {
                sh 'npm run start'
            }
        }
    }
}
