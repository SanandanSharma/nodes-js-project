pipeline {
  agent any
    
  tools {nodejs "nodejs-job"}
    
  stages {
        
     
    stage('Build') {
      steps {
        sh 'npm install'
        
      }
    }

    stage("build image"){
      steps{
        script{
          echo "building the docker image..."
         # withCredentials([usernamePassword(credentialsId:'dockerhub', passwordVariable: 'PASS', usernameVariable: 'USER' )]){
         #   sh 'docker build -t '
         # }
        }
      }
    }  
    
    }

}
