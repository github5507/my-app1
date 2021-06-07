node{
  stage ("SCM checkout"){
    git "https://github.com/github5507/my-app1"
  }
  stage("Compile-package"){
    sh "mvn package"
  }
}
