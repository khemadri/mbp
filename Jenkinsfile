pipeline{
   agent any
         stages{
           stage("hello"){
              when{
                   branch "develop"
              }
             steps{
               echo "welcome to multi-branch pipeline"
             }
           }
         }
   }
