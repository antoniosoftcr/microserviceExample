@Library('githublib') _

pipeline {
    //agent none
    stages {
        stage ('Example') {
            steps {
                // log.info 'Starting' 
                script { 
                    log.call()
                    log.info('Starting')
                    log.warning(name:'yi',msg:'Nothing to do!')
                }
                // Example of Direc call of var and resources loading
                helloWorldExternal(name:'noyi', dayOfWeek:'Thursday')
                // Example of custom step:
                mystep {
                    echo 'OMGhss!'
                }
            }
        }
    }
}