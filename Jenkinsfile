pipeline {
    agent {
        label "agent01"
    }
    options {
        buildDiscarder(logRotator(numToKeepStr: 100))
}
    stages {
        stage('Build') {
            steps {
                sh "pwd"
                sh "$HOSTNAME"
                sh "printenv | sort"
            }
        }
       
    }
}
