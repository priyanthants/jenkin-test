pipeline {
    agent any

    stages {
        stage('Install') {
            steps {
                echo 'Installing..'
                npm i
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
                npm run build
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                npm run start
            }
        }
    }
}