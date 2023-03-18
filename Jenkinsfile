pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
      	withDotNet(sdk: '.NET 6') {
	  sh '''
            dotnet restore
            dotnet build
          '''
      	}
      }
    }    
  }
}
