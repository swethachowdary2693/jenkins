pipeline {
    agent any
    environment {
        ENV_URL = "pipeline.jenkins.io"
        SSH_CRED = credentials('SSH')
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }

        stage("shell") {
            steps {
                sh "echo hai"
                sh "env"
            }
        }

    }
}


// SSH_CRED_USR
// SSH_CRED_PSW
