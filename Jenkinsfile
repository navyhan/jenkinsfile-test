pipeline {
  agent any

  stages {
    stage('build') {
      steps {
        sh 'make build'
      }
    }
    stage('test') {
      steps {
        sh 'make test'
      }
    }
    stage('package') {
      steps {
        sh 'make package'
      }
    }
    stage('publish') {
      steps {
        sh 'make publish'
      }
    }

  }
}
