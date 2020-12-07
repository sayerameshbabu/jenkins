pipeline{
  agent any
  stages{
    stage("build"){
      steps{
        script{
          sh " 'echo $hostname' "
        }
       /* sh '''
          echo "$whoami"
        ''' */
      }
    }
  }
}
