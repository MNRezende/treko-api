pipeline {
  agent {
    docker {
      image "node:8-alpine"
    }
  }
  stages {
    stages("Build") {
      steps {
        sh "npm install" 
      }
    }
  }
}
