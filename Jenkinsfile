pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
            echo "Building the code"
            sh './gradlew build --no-daemon'
            archiveArtifacts 'dist/trainSchedule.zip'
            }
        }
        
    }
}
