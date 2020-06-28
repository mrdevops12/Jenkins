pipeline {
    agent any
    stages {
        stage('Source'){
            steps {
                git 'https://github.com/spring-projects/spring-petclinic.git' 
            }
        }
        stage('Package'){
            steps {
                sh 'mvn package'
            }
        }
    }
}
