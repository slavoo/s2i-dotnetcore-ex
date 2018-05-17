node('dotnet20')
{  
  stage('checkout'){
    checkout scm
  }

  stage('Build')
  {
    sh "dotnet build"
  }
  
  stage('Publish')
  {
  }
}
