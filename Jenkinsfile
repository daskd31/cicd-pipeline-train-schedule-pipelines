pipeline {
 agent any
  stages {
    stage('Build') {
      echo 'Running build automation'
      sh './gredlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
  
}
