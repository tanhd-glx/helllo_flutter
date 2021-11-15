pipeline {
    agent {
       label "mac"
    }
    stages {
        stage('Checkout code') {
            steps {
                checkout scm
            }
        }
        stage('Hello') {
            steps {
                chek
                echo 'Hello World'
                sh 'touch ahihi'
            }
        }
    }
}
