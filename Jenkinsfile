pipeline {
  agent any
    
  tools {nodejs "nodejs-job"}
    
  stages {
        
     
    stage('Build') {
      steps {
        sh 'npm install'
        
      }
    }  
    
            
    stage('Test') {
      steps {
        sh 'node test'
      }
    }
  }
}
