pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                sh './gradlew assemble'  // TODO: Run the build
            }
        }
        stage('Test') {
            steps {
                sh './gradlew test'  // TODO: Run the tests
            }
        }
    }
}

