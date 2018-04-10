pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('stage') {
      steps {
        echo 'hello'
      }
    }
    stage('maven version') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}