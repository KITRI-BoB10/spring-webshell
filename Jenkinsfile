pipeline {
  agent any
  stages {
    stage('Git') {
      steps {
        git(url: 'https://github.com/korkeep/spring-webshell.git', branch: 'master')
      }
    }
    stage('Build') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}