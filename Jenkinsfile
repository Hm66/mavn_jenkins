pipeline {
    agent any
    triggers {
        pollSCM '* * * * *'
    }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
