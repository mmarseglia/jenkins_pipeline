pipeline {
  agent any
  stages {
    stage('stage') {
      steps {
        echo 'hello'
      }
    }
    
    stage('maven version') {
      steps {
        sh "mvn -v"
      }
  }
}
