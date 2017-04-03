pipeline {
    agent any
    stages {
        stage('first') {
            steps { 
                sh 'ping -c 10 www.apple.com'    
            }            
        }
        stage('second') {
            steps {
                sh 'ping -c 10 www.apple.com'    
            }            
        }
    }    
}
