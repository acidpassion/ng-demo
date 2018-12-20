pipeline {
    agent any
 
    stages {
        stage('Build') {
            steps {
                nodejs(nodeJSInstallationName: 'node10', configId: 'node_10.13') {
                    sh 'npm config ls'
                }
            }
        }
    }
}