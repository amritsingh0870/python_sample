#!groovy

pipeline {
    agent any {
    }

    stages {
        stage("Build") {
            steps {
                bat "python sample.py"
            }
        }
    }

    post {
        always {
            cleanWs()
        }
    }
}
