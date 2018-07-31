pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''mvn -B -DskipTests clean package  

 


 



'''
      }
    }
    stage('Deploy') {
      steps {
        sh 'sudo cp -p ./target/SreeJavaExample.war /var/lib/tomcat8/webapps/sree-bo1.war'
      }
    }
  }
}