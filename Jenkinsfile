pipeline {
    agent any
    tools {
        maven 'm3'
    }
    stages {
      stage('build') {
        steps {
          echo "Welcome to Jenkins server using pipeline!"
          sh 'mvn --version'
        }
    }
  }
}
