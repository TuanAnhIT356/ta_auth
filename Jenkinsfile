pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hello 2') {
            steps {
                telegramSend("Hello World")
            }
        }
    }
}
