pipeline {
    agent any
        stages {
        stage('Build')
    {
    steps {
        echo "Executing in Master"
        sh "hostname -i"
    }
    }
    stage('otherBuild') {
        agent {
          label 'java-slave'
        }
    steps {     
    echo "Executing in Slave"
        sh "hostname -i"
    }
}
    }
}
