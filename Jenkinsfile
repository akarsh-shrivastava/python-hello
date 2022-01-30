pipeline{
  agent any
  stages{
    stage("List"){
      steps{
        sh"""ls -lR"""
      }
    }
    stage("build"){
      steps{
        sh"""echo "build" """
      }
    }
    stage("deploy"){
      steps{
        sh"""echo "deploy" """
      }
    }
  }
}
