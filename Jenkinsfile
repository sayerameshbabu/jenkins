pipeline{
  agent any
  stages{
    stage("build"){
      steps{
        sh 'echo $hostname '
        sh '''
          echo "$whoami"
        '''
      }
    }
  }
}
