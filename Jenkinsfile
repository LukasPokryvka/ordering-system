pipeline {
  agent any
    
  tools {nodejs "node"}
    
  stages {
        
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }  
         
    stage('Move to Apache') {
      steps {
        sh 'sudo /root/./fe-admin-pipeline.sh'
      }
    }
  }
}