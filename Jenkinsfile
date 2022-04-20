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

  }
}