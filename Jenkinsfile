pipeline {
  agent any
  stages {
    stage('Build-1') {
      steps {
        echo "EXECTUING BUILD"
        sh './gradlew build --no-daemon'
        /*archiveArtifacts artifacts: dist/trainSchedule.zip*/
      } 
    }
  }
}
