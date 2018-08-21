pipeline {
    //agent any
   // agent {label 'master'}
    agent {label 'NGA01'}
    libraries {
  lib('Jenkinsfile-Shared-DevOps@master')
}
    stages {
        stage('build') {
            steps {
                Printing('Husam')
		bat 'echo hello world %DATE% > hw.txt'
		bat 'whoami'
            }
        }
    }
}
