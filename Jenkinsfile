pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project!!!'
            }
        }
        
        stage('Test') {
            steps {
                sh './testScript.sh'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying code!!!'
            }
        }
    }
}
