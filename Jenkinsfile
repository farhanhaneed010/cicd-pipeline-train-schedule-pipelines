pipeline{
  agent any
  stages{
    stage ('Build'){
     step{
        echo 'Running build automation'
        sh './gradlew build --nodaemon'
        archiveArtifact artifacts: 'dist/trainSchedule.zip'
     }
    }
  }
}
