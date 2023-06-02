pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo "Test"
                sh "mvn clean test"
            }
        }
    }
}
