pipeline {
  agent any
  tools {
        maven 'Maven_3.5.2' 
    }
  
  stages {
    stage("build") {
      steps {
        echo "Building maven project"
        mvn 'clean'
      }
    }
  }
}
