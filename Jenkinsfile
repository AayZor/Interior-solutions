pipeline{
  agent any
  stages{
    stage('SCM Checkout'){
      steps {
        git 'https://github.com/AayZor/Interior-solutions'
      }
    }
    stage('Compile-package'){
      steps {
        def mvnHome = tool name: '3.8.4', type: 'maven'
        bat 'mvn package'
      }
    }
  }
}
