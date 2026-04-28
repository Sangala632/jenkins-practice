pipeline {
    agent {
        label 'agent-1'
    } 

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

    post { 
        always { 
            echo 'I will always say Hello again!'
        }

        success { 
            echo 'If success say ..I will always say Hello again!'
        }

        
        failure { 
            echo 'If failure say ..I will always say stage is failure!'
        }
    }

}