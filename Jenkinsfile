
pipeline {
    agent any
    stages {
        stage("Build tag") {
            when {
                changeRequest()
            }
            steps {
                echo "hi"
            }
        }
    }
}
