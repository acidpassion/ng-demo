pipeline {
    agent any
 
    stages {
        stage('Build') {
            steps {
                nodejs(nodeJSInstallationName: 'Node 10.x', configId: 'node_10.13') {
                    sh 'npm config ls'
                }
            }
        }
    }
}