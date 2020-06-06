pipeline{
  agent any
    stages{
     stage('build'){
       when{
          changeset pattern: "*.WORLD.js,caseSensitive: true"
         }
        steps{
           echo "save world"
        }
     }
    }
}
          
