pipeline {
  agent {
    node {
      label 'system-hpuft-02-at'
    }

  }
  stages {
    stage('test') {
      steps {
        echo 'params.SETENV'
      }
    }
  }
  environment {
    SETENV = 'AT'
  }
}