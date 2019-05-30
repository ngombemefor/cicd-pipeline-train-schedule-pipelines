pipeline {
  agent any
  statges {
    stage ('build') {
      steps {
        echo "Running build automation"
        sh './gradlew build --no-daemon'
        archiveArtifacts: 'dist/trainSchedule.zip'
        }
       }
     }
   }
