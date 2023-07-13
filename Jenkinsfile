pipeline {
    agent any
    stages {
        stage("Build changereq") {
            when {
                changeset "*.js"
            }
            steps {
                echo "hi"
            }
        }
    }
}
