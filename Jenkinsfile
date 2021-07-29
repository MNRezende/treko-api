pipeline {
  agent {
    docker {
      image "node:8-alpine"
      label "docker-node"
    }
  }
  stages {
    stage ("Build") {
      steps {
        sh "npm install" 
      }
    }
  }
}
