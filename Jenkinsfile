pipeline {
    agent any
    tools {
        maven 'mymaven'
        jdk 'myjdk'
    }
    stages {
        stage("build code"){
            steps{
              sh "mvn clean install"
            }
        }
       
    }
}
