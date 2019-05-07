pipeline {
    agent any

        stages {
        stage('Install') {
            steps {
                echo 'Installing..'
                bat 'npm i'
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
                bat 'npm run build'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                bat 'npm run start'
            }
        }
    }
}