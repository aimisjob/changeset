pipeline{
  agent any
    stages{
     stage('build'){
       when{
          changeset pattern: "*world.js"
         }
        steps{
           echo "save world"
        }
     }
    }
}
          
