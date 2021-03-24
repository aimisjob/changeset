pipeline{
  agent any
    stages{
     stage('build'){
       when{
          changeset "*WORLD.js"
          
        }
        steps{
           echo "save world"
        }
     }
    }
}
          

