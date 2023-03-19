pipeline {
  agent any
  environment {
      DOTNET_SYSTEM_GLOBALIZATION_INVARIANT = 1
  }
  stages {
    stage('Build') {
      steps {
      	bat {
			msbuild jenkinstest-dotnetframework.sln
		}
      }
    }    
  }
}
