pipeline {
    agent any 
    
    stages {
        
        
        stage('Print') {
            steps {
                echo 'new project'
            }
        }
        
        stage('Clone') {
            steps {
                sh 'git clone -b master https://github.com/reddi122/sample.git'
            }
        }

    }
}
