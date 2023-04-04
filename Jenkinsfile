pipeline {
  agent any
  environment {
      DOTNET_SYSTEM_GLOBALIZATION_INVARIANT = 1
  }
  stages {
    stage('Pre-requisites') {
      steps {
		    script {
          bat "node -v"
          bat "npm -v"
			    bat "npm uninstall -g firebase-tools"
          bat "npm install -g firebase-tools"
          bat "firebase -V"
		    }      	
      }
    }    
  }
}
