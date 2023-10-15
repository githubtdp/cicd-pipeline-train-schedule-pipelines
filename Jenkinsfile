pipleline {
  agent any
  stages {
    stage ( 'Build') { 
      steps {
        echo'Running automatiomn'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
