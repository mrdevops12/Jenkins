pipeline {
   agent {
     }
   stages {
     stage("clone git") {
        steps {
           sh "https://github.com/mrdevops12/spring-petclinic.git"
          }
        }
     stage("build package") {
       steps {
          sh "mvn package"
         }
       }
    }
  }    
