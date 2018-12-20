pipeline {
    agent any
 
    stages {
        stage('Build') {
            steps {
                nodejs(nodeJSInstallationName: 'node11.5', configId: 'node11.5) {
                    sh 'npm config ls'
                }
            }
        }
    }
}