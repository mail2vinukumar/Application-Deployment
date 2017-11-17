pipeline {
  agent any
  stages {
    stage('Test'){
      steps{
        script{
          try{
            echo 'Done'
          }
          }catch(Exception err) {              
              throw err
          }
        }
      }
    }
  }
  post {
    always {                
        //deleteDir()
    }
  }
}
