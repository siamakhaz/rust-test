pipeline {
  agent {
    node {
      label '_DOCKER-001'
    }

  }
  stages {
    stage('Build') {
      agent {
        node {
          label '_DOCKER-001'
        }

      }
      steps {
        echo 'Building..'
        sh 'docker-compose up'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }

  }
}