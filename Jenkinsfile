pipeline{
  agent any
    stages{
     stage('build'){
       when{
          changeset glob: "*.js"
         }
        steps{
           echo "save world"
        }
     }
    }
}
          

