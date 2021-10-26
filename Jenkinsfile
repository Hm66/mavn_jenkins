node{
  stage('SCM Checkout'){
    git 'https://github.com/Hm66/mavn_jenkins'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
