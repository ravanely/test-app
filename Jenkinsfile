node{
  stage('SCM Checkout'){
    git 'https://github.com/ravanely/test-app.git'
  }
  
  stage('Compile-Package'){
    def mvnHome = tool name: 'maven-3', type: 'maven'
    
    sh 'mvn package'
    sh "${mvnHome}/bin/mvn package
  }
}
