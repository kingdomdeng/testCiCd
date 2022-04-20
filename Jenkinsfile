pipeline {
  agent any
  stages {
    stage('run') {
      steps {
        nodejs('NodeJS15') {
          sh '''pwd

npm install 

npm run build

tar -czvf testCICD.tar dist'''
        }

      }
    }

    stage('123') {
      steps {
        archiveArtifacts(artifacts: 'dist/', caseSensitive: true)
      }
    }

  }
}