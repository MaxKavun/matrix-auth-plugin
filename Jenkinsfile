@Library('shared-lib@develop') _

pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "Build"
                sh 'mvn package'
            }
        }
        stage('Test') { 
            steps {
                echo "Test"
            }
        }
        stage('Deploy') { 
            steps {
                echo "Deploy"
                sh 'mvn deploy'
            }
        }
    }
}