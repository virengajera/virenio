pipeline {
  
  agent any
  
  stages{
 
    stage("install dependency"){
     
      steps{
       
        sh "npm install"
      
      }
      
    }
    
    stage("build"){
     
      steps{
        
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
