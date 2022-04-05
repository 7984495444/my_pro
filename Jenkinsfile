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
        git branch: 'main', url: 'https://github.com/7984495444/my_pro.git'
      }
    }
  }
