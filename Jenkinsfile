pipeline{
  agent any
  tools {
    maven "3.8.4"
  }
  stages{
    stage('SCM Checkout'){
      steps {
        git 'https://github.com/AayZor/Interior-solutions'
      }
    }
    stage('Compile-package'){
      steps {
        bat 'mvn package'
      }
    }
  }
}
