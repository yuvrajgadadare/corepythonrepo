pipeline {
    agent any
    stages {
        stage("Version") {
            steps {
                sh "python3 --version"

            }
        }
        stage("hello") {
            steps {
                sh "Main.py"
            }
        }
    }
}