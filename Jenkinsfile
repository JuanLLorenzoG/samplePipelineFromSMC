// Jenkinsfile (Declarative Pipeline)

pipeline {

    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building.. no vamos1'
                script{
                def example = load '/lib/examples.groovy'
                example.example1()
                }
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