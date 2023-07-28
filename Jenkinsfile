pipeline {
    agent any

    stages {
        stage('sonor analysis') {
            steps {
                // Here, you would include the build steps for your project.
                // For example, compiling code, packaging artifacts, etc.
                echo 'sonor analysis '
            }
        }
        stage('build') {
            steps {
                // Here, you would include the build steps for your project.
                // For example, compiling code, packaging artifacts, etc.
                echo 'build'
            }
        }

        stage('Test') {
            steps {
                // Here, you would include the steps for testing your project.
                // For example, running unit tests, integration tests, etc.
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                // Here, you would include the steps to deploy your project.
                // For example, deploying to a development or production environment.
                echo 'Deploying the project...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully!'
        }
        failure {
            echo 'Pipeline execution failed!'
        }
    }
}
