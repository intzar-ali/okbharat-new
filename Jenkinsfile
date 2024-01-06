pipeline {
  agent any
  stages {
    stage('abc') {
      steps {
        build(job: 'abcdeg', waitForStart: true)
      }
    }

  }
}