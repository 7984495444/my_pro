pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo "this is build stage"
      }
    }
    stage('git clone') {
      steps {
        git branch: 'main', url: 'https://github.com/harsha7979/demo1.git'
      }
    }
  }
