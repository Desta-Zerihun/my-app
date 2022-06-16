pipeline {
    agent any
  stages {
    stage ('---clean---') {
      steps {
        sh "maven clean"
      }
     }
    stage ('--test--'){
      steps {
        sh "mvn test"
      }
    }
    stage ('--package--'){
      steps {
        sh "mvn package"
      }
    }
  }
}
