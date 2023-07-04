pipeline {
    agent any

    stages {
        stage('Unittest') {
            steps {
              sh ' echo "Unittesting"'
                
            }
        }
        stage('Lint') {
            steps {
                echo "linting"
            }
        }
        stage('Functional test') {
            steps {
                echo "testing"
            }
        }
    }
}