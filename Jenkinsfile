pipeline{
  agent any
    stages{
     stage('build'){
       when{
          changeset pattern: "*WORLD.js"
         }
        steps{
           echo "save world"
        }
     }
    }
}
          
:
