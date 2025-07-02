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
                    // if condition
                    if (course== "Jenkins")
                    println("Thanks for enrolling Jenkins")
                    else
                    println("Please register jenkins")
                //println("Thank you for installing ${course} course")
                }
                              
            }
        }
    }
}
