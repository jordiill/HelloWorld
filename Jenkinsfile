pipeline {
  agent any
  stages {
    stage('') {
      steps {
        build(job: 'Prova', propagate: true, quietPeriod: 3, wait: true)
      }
    }
  }
  environment {
    cdialeg = '0192'
  }
}