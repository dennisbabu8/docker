pipeline {
  agent any
  stages{
    stage("build") {
      steps{
        echo 'Building an application.'
      }
    }
    stage("test") {
      steps{
        echo 'Testing app.'
        script{
          if (5>3)
            echo 'Running Fine'
          else
            echo 'Error'
        }
      }
    }
    stage("deploy") {
      steps{
        echo 'Deploying the application....'
      }
    }
  }
}
