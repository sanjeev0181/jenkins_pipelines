pipeline {
  agent any
  stages {
    stage('getscm') {
      steps {
        git(url: 'https://github.com/jmstechhome/javatest.git', branch: 'master', credentialsId: 'github_credentials')
      }
    }

    stage('') {
      steps {
        sh '''javac HelloWorld.java
java HelloWorld'''
      }
    }

  }
}