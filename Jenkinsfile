pipeline {
   agent any
   stages {
     stage ('Build') {
       steps
         echo 'Running build automation'
         sh './gradlew bild --no-daemon'
         archiveArtifacts atifacts: 'dist/trainSchedule.zip'
   }   
}
