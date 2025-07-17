Jenkinsfile

@Library('githublib') _

pipeline {
    agent none
    stages {
        stage ('Example') {
            steps {
                // log.info 'Starting' 
                script { 
                    log .call
                    log.info 'Starting'
                    log.warning 'Nothing to do!'
                }
            }
        }
    }
}