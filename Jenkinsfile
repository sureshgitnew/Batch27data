pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo "Hello from ${env.BRANCH_NAME}"
            }
        }
        stage('Hello1') {
            steps {
                echo "Hello1 from ${env.BRANCH_NAME}"
            }
        }
    }
}
