pipeline {
    agent {
        label 'java-label'
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
            input {
                message "Do you want to deploy to Prod environment?"
                ok "Yes"
                submitter "sujanacademy, mahadev"
            }
            steps {
                echo "Deploying the project to Prod environment"
            }
        }
    }
}
