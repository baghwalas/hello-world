pipeline {
    agent any
    tools {
        maven 'mymaven'
        jdk 'myjdk'
    }
    stages {
        stage("build code"){
            agent {
                        label "Slave1"
                    }
            steps{
              sh "mvn clean install"
            }
        }
       
    }
}
