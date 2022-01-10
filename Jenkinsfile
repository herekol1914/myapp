node{
  stage('SCM Checkout')
  git 'https://github.com/javahometech/my-app/new/master/src'
  }
stage('Compile-Package'){
  sh 'mvn package'
  }   
}
