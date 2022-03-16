pipeline { agent any

stages {

stage("build"){
        steps{
          echo 'Building Application'
          
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

