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
        sh "[-e *.tar.gz] && rm -rf *.tar.gz"
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
