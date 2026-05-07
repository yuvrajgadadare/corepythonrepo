pipeline {
    agent any
    stages {
        stage("Version") {
            steps {
                bat "python --version"

            }
        }
        stage("hello") {
            steps {
                bat "Main.py"
            }
        }
    }
}
