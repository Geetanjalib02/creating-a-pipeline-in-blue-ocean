pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'Build', propagate: true, quietPeriod: 10, wait: true)
      }
    }

  }
}