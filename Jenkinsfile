pipeline {
agent any
stages {
 stage ('build'){
  steps {
   echo 'Runing build automation'
   sh './gradlew build automation'
   archiveArtifacts artifacts: 'dist/trainSchedule.zip'
  }
 }
 }
}
