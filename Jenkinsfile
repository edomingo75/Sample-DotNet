node{
 
  stage ('SCM Checkout'){
    git branch: 'main', credentialsId: '1892ba7c-9a00-47b1-8cdb-783d7f57fbee', url: 'https://github.com/edomingo75/Sample-DotNet'
    
  }
 stage('Build + SonarQube analysis'){
   
   dotnetClean()
   dotnetBuild()
  
   
  }
}
