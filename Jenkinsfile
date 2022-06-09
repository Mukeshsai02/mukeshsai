pipeline {
    agent any
    
    tools {
        jdk 'java8'
        maven "Maven_3.3.9"
    }
    
    stages 
    {
        stage('git clone'){
            steps {
                git 'https://github.com/Mukeshsai02/mukeshsai.git'
            }
        }
        stage('Compile and Build'){
            steps {
                sh '''
                mvn clean install -U -Dmaven.test.skip=true
                '''
            }
        }
        
    }
}
