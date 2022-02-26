pipeline {
  agent any
  stages {
    stage('PIPELINE1') {
      steps {
        build(job: 'JOB-1', propagate: true)
      }
    }

  }
}