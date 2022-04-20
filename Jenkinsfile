pipeline {
  agent any
  stages {
    stage('run') {
      steps {
        git(url: 'https://github.com/kingdomdeng/testCiCd.git', branch: 'master', changelog: true)
        sh 'npm run build'
      }
    }

  }
}