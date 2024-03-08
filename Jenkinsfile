pipeline {
  agent any
  stages {
    stage('Build') {
      steps{
        build 'PES1UG21CS108-1'
        sh 'g++ main.cpp -o output'
      }
    }

    stage('Test') {
      steps {
        sh './output'
      }
    }ujiAbieajabjboshcabuadyva Lbuvbobsub uoabduoal bauyiv iua

    stage('Deploy') {
      steps {
        echo 'deploy'
      }
    }
  }

  post{
    failure{
      error 'Pipeline Failed'
    }
  }
}
