pipeline {
  agent any
  stages {
    stage('Welcome') {
      parallel {
        stage('FirstStage') {
          steps {
            echo 'Hello World'
          }
        }
        stage('FirstParallelStage') {
          steps {
            echo 'Other Hello World'
          }
        }
      }
    }
  }
}