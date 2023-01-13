pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'python3 hello.py'
                echo 'Hello JENKSINS World'
            }
        }
        stage('Java') {
            steps {
                sh 'java -version'
                echo 'Hello JAVA World'
            }
        }
    }
}
