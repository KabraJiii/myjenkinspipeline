pipeline {
    agent any
    stages {
        stage('SCM'){
            steps {
                echo "Git pull my code 1"
                echo "Git pull my code 2"
            }
        }
        stage('Deploy'){
            steps {
                echo "Deploying my code"
            }
        }
        stage('Test'){
            steps {
                echo "Testing my code"
            }
        }
    }
}