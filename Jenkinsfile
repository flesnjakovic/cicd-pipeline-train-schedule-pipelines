pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Building...'
        sh './gradlew build'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
