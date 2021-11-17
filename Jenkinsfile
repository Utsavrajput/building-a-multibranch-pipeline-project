pipeline {
    agent {
        label "agent01"
    }
    options {
        buildDiscarder(logRotator(daysToKeepStr: '100'))
}
    stages {
        stage('Build') {
            steps {
                sh "pwd"
                
                sh "printenv | sort"
            }
        }
       
    }
}
