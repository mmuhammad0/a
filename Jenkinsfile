pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            input(message: 'push?', ok: 'yes')
          }
        }

        stage('2') {
          steps {
            input(message: 'back', ok: 'yes')
          }
        }

      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'mam'
          }
        }

        stage('') {
          steps {
            echo 'aaaaa'
          }
        }

      }
    }

  }
}