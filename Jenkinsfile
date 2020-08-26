pipeline {
  agent {
    dockerfile {
      filename 'Test'
    }

  }
  stages {
    stage('Test') {
      steps {
        powershell(script: 'write-host "Hello World"', encoding: 'UTF-8')
      }
    }

  }
}