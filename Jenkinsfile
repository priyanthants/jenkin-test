node('docker') {
    checkout scm
    stage('Build') {
        docker.image('node:10.15.0').inside {
            sh 'npm --version'
        }
    }
}