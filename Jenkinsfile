pipeline {
  agent any
  stages {
    stage('Add a file') {
      agent any
      steps {
        writeFile(file: 'test.txt', text: 'created using pipeline')
      }
    }
  }
  environment {
    filename = 'test.txt'
  }
}