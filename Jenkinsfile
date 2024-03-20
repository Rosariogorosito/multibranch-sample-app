pipeline {
  agent any
  options {
    buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '' numToKeepStr: '5')
    disableConcurrentBuilds()
  }
  stages {
    stages('Hello') {
      steps  {
        echo "hello"
      }
    }
  }
}

