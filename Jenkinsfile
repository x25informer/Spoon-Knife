pipeline {
    agent any
    stages {
        stage('Stage1') {
            steps {
                echo "My Pipe"
            }
        }
        stage('Stage2') {
            steps {
                echo "My build id:" $BUILD_ID
            }
        }
    }
}
