pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
       sh 'chmod a+x run_build_script.sh'
       sh './run_build_script.sh'
     }
    }
    stage('Test') {
      steps {
       echo "Run tests" 
      }
    }
  }
}
