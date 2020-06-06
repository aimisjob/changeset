pipeline{
  agent any
    stages{
     stage('build'){
       when{
          changeset pattern: "*.WORLD.js,casesensitive: true"
         }
        steps{
           echo "save world"
        }
     }
    }
}
          
