pipeline {
    agent {
        docker { image 'node:20.11.1-alpine3.19' }
    }
    stages {
        stage('Build') {
            steps {
                // echo 'Building Hello, world!'
                console.log("Running NodeJS Env.")
            }
        }
        stage('Test') {
            steps {
                echo 'Testing Hello, world!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying Hello, world!'
            }
        }
    }
}
