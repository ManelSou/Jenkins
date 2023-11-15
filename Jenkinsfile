pipeline {
  agent any
  stages {
    stage('Tests') {
      steps {
        echo 'demarrage du stage test'
        sleep 30
        echo 'Fin du stage test'
      }
    }

    stage('build') {
      steps {
        echo 'StartBuild stage '
        sleep 30
        echo 'Fin du build'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Début Deploy'
        sleep 30
        echo 'fin du deploy'
      }
    }

  }
}