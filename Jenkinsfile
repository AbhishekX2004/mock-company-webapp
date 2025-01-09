pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Starting Build...'
                // Build the project
                sh './gradlew assemble'
            }
        }

        stage('Test') {
            steps {
                echo 'Running Tests...'
                // Run the tests
                sh './gradlew test'
            }
        }
    }
}
