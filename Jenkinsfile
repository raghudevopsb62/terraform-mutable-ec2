pipeline {

  agent {
    node { label 'workstation' }
  }

  stages {
    stage('Check Code Style') {
      steps {
        sh 'terraform fmt -check -recursive -diff'
      }
    }
  }

}
//
