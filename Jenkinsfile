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
        bat 'echo The project is built to run safely'
      }
    }
  }
}
