pipeline {
    agent any
    stages {
        stage ('Build') {
            echo "Building the code"
            sh './gradlew build'
            archiveArtifacts 'dist/trainSchedule.zip'
        }
        
    }
}
