pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        fileExists 'README.MD'
      }
    }
    stage('test') {
      steps {
        echo 'file exists'
      }
    }
    stage('deploy') {
      steps {
        writeFile(file: 'test2', text: 'new file')
      }
    }
  }
}