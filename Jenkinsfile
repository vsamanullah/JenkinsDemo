pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    } 
    post {
        always {
                echo 'Post action for jenkins'
                echo 'One more Post action for jenkins'
            }
        }
}
