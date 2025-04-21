pipeline {
  agent: any
  stages {
    stage('Build') {
      steps {
        sh './gradlew assemble'
      }
    }
    stage('Test') {
      sh './gradlew test'
    }
  }
}
