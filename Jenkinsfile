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
                echo "My build id: ${env.$BUILD_ID} and my build number ${env.$BUILD_NUMBER}" 
            }
        }
    }
}
