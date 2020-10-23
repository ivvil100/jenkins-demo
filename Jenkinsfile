pipeline {
  agent any
  
  stages {
    stage("build") {
      steps {
        echo "Building maven project"
        withMaven {
            sh "mvn clean install"
          } 
      }
    }
  }
}
