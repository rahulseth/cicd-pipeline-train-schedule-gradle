pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
               echo "my test"
               sh './gradlew build --no-daemon'
               archieveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        } 
    }
}
