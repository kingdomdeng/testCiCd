pipeline {
  agent any
  stages {
    stage('run') {
      steps {
        nodejs 'NodeJS15'
        sh 'npm run build'
      }
    }

  }
}