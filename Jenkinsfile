pipeline{
  agent any
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
