pipeline {
    agent any 
    stages {
        stage('checkout'){  
            steps {
                git 'https://github.com/vanimadhav/warrepo.git'
            }
        }
        stage('build'){
            steps {
                 sh 'mvn clean package'
     :       }
            }
    }
