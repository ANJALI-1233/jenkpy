pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        bat 'py hello.py'
      }
    }
  }
}
