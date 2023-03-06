pipeline {
  
  agent any
  
  stages{
 
    stage("install dependency"){
     
      steps{
       
        sh "npm install"
        sh "echo 'hooks demo 1'"
      
      }
      
    }
    
    stage("build"){
     
      steps{
        
        sh "tar cvf virenio.tar.gz public package.json server.js"
      }
      
    }
    
    stage("deploy"){
     
      steps{
       
        sh "echo 'Deploying is in process'"
        
      }
      
    }
    
  }
  
}
