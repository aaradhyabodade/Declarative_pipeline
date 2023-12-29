pipeline {
agent any 
stages {
       stage('SCM'){
               steps {
                      echo"git pull my code step1"
                      echo"git pull my code step2"
                   }
        }
       stage('Deploy'){
               steps {
                      echo "deploying my code"
               }
       }
       stages('Test'){
               steps {
                      echo "Test my final webapp"
               }
       }
      }
    }
