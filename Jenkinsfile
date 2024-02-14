pipeline {
  agent {
    node {
      label 'Unit Test'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'first jenkins pipeline'
        sh './mvnw clean compile'
      }
    }

    stage('UnitTest') {
      steps {
        echo 'UnitTest in progress'
        sh './mvnw test'
      }
    }

  }
}