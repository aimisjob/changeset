pipeline{
  agent any
    stages{
     stage('build'){
       when{
          changeset "*WORLD.js",caseSensitive: true
          
        }
        steps{
           echo "save world"
        }
     }
    }
}
          

