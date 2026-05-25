pipeline {
    agent any

    stages {

        stage('Show Branch') {
            steps {
                echo "Building branch: ${env.BRANCH_NAME}"
            }
        }

        stage('Build') {
            steps {
                echo "Building project..."
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }
    }
}
