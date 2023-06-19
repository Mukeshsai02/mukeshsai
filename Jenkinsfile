pipeline {
    agent any
    
    tools {
        jdk 'Java8'
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
                mvn clean 
                '''
            }
        }
        
    }
}
