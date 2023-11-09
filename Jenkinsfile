pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hello'
          }
        }

        stage('Test') {
          steps {
            echo 'Testing STarted'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        sleep 10
      }
    }

    stage('Post') {
      steps {
        writeFile(file: 'c:\\Users\\user\\Desktop\\test.txt', text: 'It Works')
      }
    }

  }
}