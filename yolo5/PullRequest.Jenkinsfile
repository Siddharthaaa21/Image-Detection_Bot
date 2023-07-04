pipeline {
    agent any

    stages {
        stage('Unittest') {
            steps {
              sh ' echo-info "Running unit tests"'
                
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