pipeline {
  agent any 
  stages {
    stage ('build') {
      steps{
        echo 'Running build Automation'
        sh './gradlew build' --no-daemon'
        archiveArtificats artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
  
