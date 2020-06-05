pipeline {
    agent any
    environment {
        CI = 'true'
        PATH = "C:\\WINDOWS\\SYSTEM32"
    }
    tools {nodejs "nodejs"}
    stages {
        stage('Build') {
            steps {
                bat label: '', script: 'call npm install'     
            }
        }
            
        stage('Deliver') {
            steps {
                bat label: '', script: 'call deliver.bat' 
            }
        }
       
    }
}
