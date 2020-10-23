pipeline {
  agent any
  
  stages {
    stage("build") {
      steps {
        echo "Building maven project"
        maven(maven : 'Maven_3.5.2'){
                 bat "mvn clean"
                }
      }
    }
  }
}
