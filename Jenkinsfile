pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "EXECTUING BUILD"
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: dist/trainSchedule.zip
      } 
     steps
      {
        echo "BUILD COMPLETED"
      }
    }
  }
}
