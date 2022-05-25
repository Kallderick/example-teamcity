pipeline {
  agent any
  stages {
    stage('First stage'){
      steps {
        git clone https://github.com/Kallderick/example-teamcity.git
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
