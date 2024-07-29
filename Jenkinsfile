pipeline {
  agent { dockerfile true }
  stages {
    stage('Test') {
      steps {
        echo 'Versions:'
        sh '''
          node --version
          git --version
          curl --version
        '''
      }
    }
  }
}
