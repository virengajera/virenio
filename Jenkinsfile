pipeline {
  
  agent any
  
  stages{
 
    stage("Installation"){
     
      steps{
       
        sh "npm install"
      
      }
      
    }
    
    stage("Build"){
     
      steps{
        sh "rm -rf *.tar.gz || true"
        sh "tar cvf virenio-$BUILD_NUMBER.tar.gz public package.json server.js"
      }
      
    }
    
    stage("deploy"){
     
      steps{
       
        sh "echo 'Deploying is in process'"
        
      }
      
    }
    
  }
  
}
