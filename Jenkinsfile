pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('build') {
      steps {
        sh 'python3 py2.py'
      }
    }
  }
}
