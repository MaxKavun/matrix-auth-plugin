@Library('shared-lib') _

pipeline {
    agent any
    options {
        disableConcurrentBuilds()
    	buildDiscarder(logRotator(numToKeepStr: '10'))
	}
    stages {
        stage('Build') { 
            steps {
                echo "Build"
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
