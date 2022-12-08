pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Jenkins test pipeline'
          }
        }

        stage('Fetch the code') {
          steps {
            git(url: 'https://github.com/vsknalli/blueocean.git', branch: 'master')
          }
        }

      }
    }

  }
}