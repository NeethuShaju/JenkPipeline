pipeline {
  agent any
  stages {
    stage ('Build')
      {
        steps {
              echo 'This is Build step in Jenkins Pipeline'
              }
        
     stage ('Get Input from user')
        {
          steps {
              input('Do you want to proceed?')
                }
       
        }
      }
  }
}
