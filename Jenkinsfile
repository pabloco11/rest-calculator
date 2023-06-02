pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                mvn clean install test
            }
        }
    }
}
