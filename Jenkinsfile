pipeline{
  agent any
  stages{
    stage("Deploy"){
      steps{
        echo "test successful"
        bat"mvn compile"
      }
    }
    stage("Build"){
      steps{
        echo "build successful"
        bat"mvn clean"
      }
    }
    stage("Test"){
      steps{
        echo "test successful"
        bat"mvn test"
      }
    }
  }
}
    
