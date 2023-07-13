
pipeline {
    agent any
    stages {
        stage("Build changereq") {
            when {
                changeRequest()
            }
            steps {
                echo "hi"
            }
        }
    }
}
