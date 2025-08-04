pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'echo Hello World'
                bat 'javac .java'
                bat 'java Hello' 
            }
        }
    }
}
