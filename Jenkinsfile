pipeline {
    agent any
    tools {
        maven 'localmaven'
    }
    stages {
        stage('buildStage') {
            steps {
                echo "Building a maven project........!"
                sh 'echo "aaaa"'
            }
        }
        stage('testingCode') {
            steps {
                echo "Testing........!"
               sh 'echo "aaaa"'
            }
        }
        stage('Clean up the Environment') {
            steps {
                echo "Cleaning up........!"
                cleanWs()
            }
        }
        
    }
}
