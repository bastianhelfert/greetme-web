pipeline {
  agent {
    docker {
      image 'maven:3.5.0'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}