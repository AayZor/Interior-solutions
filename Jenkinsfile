pipeline{
  agent any
  tools { 
        maven 'Maven 3.8.4' 
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
