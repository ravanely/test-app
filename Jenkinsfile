node{
  stage('SCM Checkout'){
    git 'https://github.com/ravanely/test-app'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
