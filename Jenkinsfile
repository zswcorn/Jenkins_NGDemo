pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo '${WORKSPACE}'
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
}