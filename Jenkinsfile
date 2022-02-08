pipeline{
  agent any
  stages{
    stage('Build'){
      when{
        changeRequest()
      }
      steps{
        echo "Main branch changing request"
      }
    }
  }
}
