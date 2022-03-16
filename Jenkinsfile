pipeline { agent any

stages {

stage("cloning git agent repository"){
        steps{
              sh 'git remote set-url origin git@github.com:Kubilay6634/agent-information1.git'
              git branch: 'main', credentialsId: 'forjenkins', url: 'https://github.com/Kubilay6634/agent-information1'
          }
}
        

stage("invoke"){
        steps{
          build job: 'java-html-builder'
          
          }
}

        
stage("test"){
        steps{
          echo 'Testing Application'
          
          }
}


stage("deploy"){
        steps{
          echo 'Deploying Application'
          
          }
}

}
}

