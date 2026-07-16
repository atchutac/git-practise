pipeline {
    agent any

    parameters {
        string(name: 'APP_NAME', defaultValue: 'MyApp', description: 'Enter Application Name')
        choice(name: 'ENVIRONMENT', choices: ['Development', 'Testing', 'Production'], description: 'Select Environment')
    }

    stages {

        stage('Build') {
            steps {
                echo "Application: ${params.APP_NAME}"
                echo "Environment: ${params.ENVIRONMENT}"
            }
        }

    }
}
