pipeline{
  agent any
  stages{
    stage("build"){
      steps{
         sh 'echo $(whoami)'
        sh 'hostname'
        sh 'sudo yum install vim -y'
      }
    }
}
}
