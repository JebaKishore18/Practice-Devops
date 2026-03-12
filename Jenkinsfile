pipeline 
{
agent any
stages{
    stage('Checkout')
      {
      steps {https://github.com/JebaKishore18/Practice-Devops.git }
      }
    stage ('Publish'){
      steps {
        publishHTML([
          allowmissing:true,
          alwaysLinktoLastBuild:false,
          keepAll:false,
          reportDir:'.',
          reportFiles:'love.html' ,
          reportName:'My html report' 
        ])
      }
    }
  }

}
