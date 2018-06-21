
pipeline {
  agent any
  stages {
    stage('init') {
      script {
        echo "init..."
      }
    }
    
    stage('checkout') {
      script {
        echo "checkout..."
      }
    }
  
  }

  post {
    always {
      script {
        echo "post..."
      }
    }
  }
}
