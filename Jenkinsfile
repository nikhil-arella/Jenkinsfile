pipeline {
  agent any
  stages {
     stages('Jenkinsfile') {
        steps{
           sh "ts -la"
           sh "cat Jenkinsfile"
           sh "chmod 700 ./script.sh"
           sh "./script.sh"
          
        }
       
     }
      stages('Jenkinsfile') {
         steps{
            sh "ls -la"
            sh "cat Jenkinsfile"
            sh "pwd"
         }
      }
   }
}           
         
