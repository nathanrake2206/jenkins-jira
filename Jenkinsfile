pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('python-jenkins') {
      steps {
        sh 'pip install python-jenkins'
      }
    }
    stage('build') {
      steps {
        sh 'python3 py2.py'
      }
    }
  }
}
