pipeline {
  agent any
  stages {
    stage('PIPELINE1') {
      steps {
        build(job: 'JOB-1', propagate: true)
      }
    }

    stage('') {
      steps {
        build(job: 'JOB-2', propagate: true)
      }
    }

  }
}