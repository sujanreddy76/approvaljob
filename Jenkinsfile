pipeline {
    agent {
        label 'java-slave'
    }
    stages {
        stage('Build') {
            steps {
                echo "Building the project"
            }
        }
        stage('Test') {
            steps {
                echo "Testing the project"
            }
        }
        stage('DevDeploy') {
            steps {
                echo "Deploying the project to Dev environment"
            }
        }
         stage('TestDeploy') {
            steps {
                echo "Deploying the project to Test environment"
            }
        }
         stage('ProdDeploy') {
            steps {
                echo "Deploying the project to Prod environment"
            }
        }
    }
}
