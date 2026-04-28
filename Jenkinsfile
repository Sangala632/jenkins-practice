pipeline {
    agent any 

    stages{
        stage('Build') {
            steps {
                echo "Building the application"
            }
        }

        stage('Test') {
            steps {
                echo "Testing the build application"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the application in vm "
            }
        }

        stage('Deploy-2') {
            steps {
                echo "optional only"
            }
        }
    }

}