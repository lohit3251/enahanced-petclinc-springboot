pipeline {
    agent any
    tools{
        maven 'mymaven'
    }
    stages {
        stage('Checkout FROM GIT') {
            steps {
                git branch: 'prod' , url: 'https://github.com/bkrrajmali/enahanced-petclinc-springboot.git'
        }
      }
      stage('compile with maven'){
        steps{
            sh 'mvn compile'
        }
      }
    
      
      
        }

    }

