pipeline {

  agent any
  
  stages {
    
    stage("build") {
       steps {
         echo 'building the application, do you wish to continue?'
      }
    }
     stage("test") {
       steps {
         echo 'testing the application...'
      }
    }
     stage("deploy") {
       steps {
         echo 'deploying the application...'
      }
    }
  }
}
  
