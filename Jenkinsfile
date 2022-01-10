node{
  stage('SCM Checkout')
  git 'https://github.com/javahometech/my-app/new/master/src'
  }
stage('Compile-Package'){
  //get maven homepath
  def mvnHome = tool name: 'maven-3', type: 'maven'
  sh "${mvnHome}/bin/mvn/mvn package"
  }   
}
