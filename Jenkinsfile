pipeline {
  agent {
    docker {
      image '3.6.3-jdk-11-openj9'
    }

  }
  stages {
    stage('clone') {
      steps {
        git 'https://github.com/subhash311992/india.git'
      }
    }

    stage('build') {
      steps {
        sleep 5
      }
    }

    stage('deploy') {
      steps {
        echo 'my'
      }
    }

  }
}