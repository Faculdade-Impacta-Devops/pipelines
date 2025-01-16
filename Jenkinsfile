pipeline {
    agent any
      tools {
        nodejs 'nodeRecent' 
      }
    environment { 
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo build'
            }
        }
        stage('Test') {
            steps {
                sh 'echo test'
            }      
        }

        stage('Deploy for production') {       
            steps {
                 sh 'echo deploy'
            }
        }      
    }
}
