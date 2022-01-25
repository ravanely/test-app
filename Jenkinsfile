node{
  stage('SCM Checkout'){
    git 'https://github.com/ravanely/test-app.git'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
