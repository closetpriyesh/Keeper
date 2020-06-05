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
<<<<<<< HEAD
=======
            }
        }
        
         stage('Test') {
            steps {
                bat label: '', script: 'call test.sh' 
>>>>>>> 43ae9e4d420c51908e4e259e4406d4e463c924bf
            }
        }
        
        stage('Deliver') {
            steps {
<<<<<<< HEAD
                bat label: '', script: 'call deliver.bat' 
=======
                bat label: '', script: 'call deliver.sh' 
                input message: 'Finished using the web site? (Click "Proceed" to continue)'
                bat label: '', script: 'call kill.sh' 
>>>>>>> 43ae9e4d420c51908e4e259e4406d4e463c924bf
            }
        }
       
    }
}
