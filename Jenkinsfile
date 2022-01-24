pipeline{
  stage('SCM Checkout'){
    steps {
      git 'https://github.com/AayZor/Interior-solutions'
    }
  }
  stages('Compile-package'){
    steps {
      bat 'mvn package'
    }
  }
}
