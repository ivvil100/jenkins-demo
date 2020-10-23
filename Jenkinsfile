pipeline {
  agent any
  
  stages {
    stage("build") {
      steps {
        echo "Building maven project"
        sh 'mvn build'
      }
    }
  }
}
