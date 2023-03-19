pipeline {
  agent any
  environment {
      DOTNET_SYSTEM_GLOBALIZATION_INVARIANT = 1
  }
  stages {
    stage('Build') {
      steps {
		script {
			bat "msbuild jenkinstest-dotnetframework.sln"			
		}      	
      }
    }    
  }
}
