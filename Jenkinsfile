pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('TestStage') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}