pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''mvn -B -DskipTests clean package  

 


 



'''
        sh 'stash name: \'war\', includes: \'target/**\''
      }
    }
  }
}