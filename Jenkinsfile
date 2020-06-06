pipeline{
  agent any
    stages{
     stage('build'){
       when{
          changeset pattern: "*.world.js", caseSensitive: true
         }
        steps{
           echo "save world"
        }
     }
    }
}
          
