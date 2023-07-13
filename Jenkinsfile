pipeline {
    agent any
    stages {
        stage("Build changereq") {
            when {
                changeset glob: *.js*
            }
            steps {
                echo "hi"
            }
        }
    }
}
