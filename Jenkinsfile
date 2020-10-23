pipeline {
  agent any
  
  stages {
    stage("build") {
      steps {
        echo "Building maven project"
        withMaven {
            bat "mvn clean install"
          } 
      }
    }
  }
}
