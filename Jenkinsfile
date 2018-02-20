pipeline {
  agent any
  stages {
    stage('inicio') {
      parallel {
        stage('inicio') {
          steps {
            sh 'echo hola mundo'
          }
        }
        stage('hola') {
          steps {
            echo 'hola perro'
          }
        }
      }
    }
    stage('end') {
      steps {
        echo 'end'
      }
    }
  }
}