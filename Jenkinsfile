Jenkinsfile (Declarative Pipeline)
pipeline {
  agent { docker { image 'maven:3.3.3' }}
  stages {
    stages ('build') {
      steps {
        sh 'mvn --version'
       }
     }
   }
 }
  
