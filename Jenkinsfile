pipeline {
    agent any
    stages {
        stage('Build1') {
            steps {
                echo "******** coming from build1 stage"
            }
        }
        stage ('groovystage') {
            steps {
                script {
                     //Define a variablename ="value"
                    def course = "Jenkins"
                println("Thank you for installing ${course} course")
                }               
              
            }
        }
    }
}
