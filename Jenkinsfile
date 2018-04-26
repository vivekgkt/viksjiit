pipeline {
  agent any
  stages {
    stage('process') {
      environment {
        java_home = 'C:\\Program Files\\Java\\jdk1.8.0_161\\bin\\'
        MAVON_HOME = ' C:\\apache-maven-3.5.3\\bin\\'
      }
      steps {
        echo 'hi message'
      }
    }
    stage('build') {
      steps {
        bat 'mvn clean compile'
      }
    }
  }
}