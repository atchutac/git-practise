pipeline {
    agent any

    environment {
        APP_NAME = "MyApp"
        VERSION = "1.0"
    }

    stages {

        stage('Build') {
            steps {
                echo "Building ${APP_NAME}"
            }
        }

        stage('Test') {
            steps {
                echo "Testing Version ${VERSION}"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying ${APP_NAME} Version ${VERSION}"
            }
        }

    }
}
