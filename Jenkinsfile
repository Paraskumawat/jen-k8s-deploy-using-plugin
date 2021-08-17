pipeline{
  agent any
 
  stages{
    stage('Deploy'){
      steps{
        kubernetesDeploy(configs: "deploy.yml", kubeconfigId: "mykubeconfigfile")
    
      }
    }
  }
}
