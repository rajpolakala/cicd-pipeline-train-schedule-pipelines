pipeline {
    agent any
    stages {
        stage ('Build') {
            echo "Building the code"
            sh './gradlew build --no-daemon'
            archiveArtifacts 'dist/trainSchedule.zip'
        }
        
    }
}
