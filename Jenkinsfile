// Jenkinsfile (Declarative Pipeline)

pipeline {

    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building.. no vamos1'
                def rootDir = pwd()
                def example = load "${rootDir}/lib/cowsay.groovy"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing.. no vamos2'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.... no vamos3'
            }
        }
    }
}