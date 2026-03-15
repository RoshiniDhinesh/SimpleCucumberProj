pipeline{

  agent any
  stages{
    stage('checkout code'){
      steps{
        git 'https://github.com/RoshiniDhinesh/SimpleCucumberProj'
      }
    }
    stage('Build')
    {
      septs{

        sh 'echo Building the application'
      }
    }
    stage ('Test'){
      steps{
        sh 'echo running tests'
      }
    }
    stage('Deploy'){
      steps{
        sh 'echo Deploying'
      }

    }





    
  }
}
