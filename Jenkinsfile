pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
       stage('Test') {
            steps {
                echo 'Hello World'
            }
        }
       stage('Deploy') {
            steps {
                echo 'Hello World - Deploy'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
