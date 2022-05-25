pipeline {
  agent any
  stages {
    stage('First stage'){
      steps {
        mvn clean install 
      }
    }
    stage('Second stage'){
      steps {
        echo "And I'm too"
      }
    }
  }
}
