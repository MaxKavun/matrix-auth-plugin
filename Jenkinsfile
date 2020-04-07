@Library('shared-lib@develop') _

pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "Build"
                updateVersions()
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
            }
        }
    }
}