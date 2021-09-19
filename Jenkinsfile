pipeline {
    agent any

    stages {
        stage('hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post {
        always {
            echo "always"
        }
        failure {
            echo "failure"
        }
    }
}
