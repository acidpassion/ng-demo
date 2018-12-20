node {
    stage('check tools') {
        sh "node -v"
        sh "npm -v"
    }

    stage('checkout') {
        checkout scm
    }

    stage('npm install') {
        sh "npm install"
    }

    stage('unit tests') {
        sh "ng test"
    }

    stage('protractor tests') {
        sh "ng e2e"
    }

    stage('deploying') {
        sh '''
        # exit 1 on errors
        set -e
        # deal with remote
        echo "am just a message..."
        '''
    }
}
