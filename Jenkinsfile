pipeline {
    agent any
    stages {
        stage("Build changereq") {
            when {
                changeset "*.jst"
            }
            steps {
                echo "hi there is no jst file"
            }
        }
    }
}
