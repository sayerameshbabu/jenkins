pipeline{
  agent any
  stages{
    stage("build"){
      steps{
        sh 'npm --version'
        sh 'echo $hostname '
        sh '''
          echo "$whoami"
        '''
      }
    }
  }
}
