pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('satge 2 ') {
            agent{
                docker{
                    image 'node:18-alpine'
                }
            }
            steps {
                echo 'Hello World'
                sh 'docker -v'
            }
        }
    }
}