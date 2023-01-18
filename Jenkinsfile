pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
               
           sh 'zip AgentScript-${BUILD_NUMBER}.zip *  --exclude Jenkinsfile pkg-installation pkg-modification1 pkg-modification2 docker'  
            
            }
        }
        
    }
}