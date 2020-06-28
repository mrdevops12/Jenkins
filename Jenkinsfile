pipeline {
   agent any
   stages {
     stage("clone git") {
        steps {
            git "https://github.com/mrdevops12/spring-petclinic.git"
          }
        }
     stage("build package") {
       steps {
          sh "mvn package"
         }
       }
    }
  }    
