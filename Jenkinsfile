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

  }
}