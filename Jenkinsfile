pipeline {
    agent any
 
    stages {
        stage('Build') {
            steps {
                nodejs(nodeJSInstallationName: 'node 10.x', configId: 'node_10.13') {
                    sh 'npm config ls'
                }
            }
        }
    }
}