pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project!!!'
                echo pwd()
            }
        }
        
        stage('Test') {
            steps {
                sh './testScript.sh'
            }
        }
    }
}
